## Hi there 👋

My name is Ricky, and for most of my life, I thought I'd never be able to write any code at all. 

In september of 2024, I received a diagnosis for ADHD at 27 years old and after four months of treatment, I created Nexus, a tiny proof-of-concept social network written fully in Typescript, with Hono as a backend and React as a frontend (private repo, will share the link here soon).

## What I have been up to lately
This summer, I have been exploring new languages as I wasn't fully satisfied with using Typescript as my backend language.

So I spent 1 month learning Go, and in that process, I created 2 libraries:
- [protoschema-go](https://github.com/Rick-Phoenix/protoschema-go), for generating protobuf files from declarative schemas written in go (with a plugin to generate ConnectRPC handlers using the same metadata extracted from those schemas).
- [querygen](https://github.com/Rick-Phoenix/querygen), which is a small helper library that generates most if not all of the boilerplate for making aggregated sqlite queries with sqlc.

And then after that, I dived into Rust, and I have really fallen in love with it. 
So after 1 month of learning it, I released my first crate: [protocheck](https://crates.io/crates/protocheck), a validation library that leverages protovalidate annotations to automatically generate validation logic in Rust. 

## Projects and ideas for the near future
- ~Porting protoschema-go to rust (yes, I dislike writing proto files that much)~  Done, that is now [protoschema](https://github.com/Rick-Phoenix/protoschema)
- Including more common protobuf types in my [proto-types](https://crates.io/crates/proto-types) crate
- Probably a few other libraries to make working with protobuf a smoother process
- Refactor a library I wrote in Typescript for generating boilerplate for TS projects, potentially porting it to Go or Rust
- Diving back into Sveltekit (which is not my frontend framework of choice) and tauri to build a desktop app
