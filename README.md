## Hi there 👋

My name is Ricky, and for most of my life, I thought I'd never be able to write any code at all. 

Before my ADHD diagnosis in september of 2024, I had never written a single line of code in my life. After starting treatment, I have finally become able to do the thing that I love doing the most. 

I started coding following the open source [Odin Project](https://www.theodinproject.com/support_us), and after 4 months, I released my first full-stack project, which is a proof-of-concept social network inspired by Reddit. 

After spending some time working on some libraries in Typescript, I realized that I wanted to try out other languages for the backend, so I started exploring Go.

So I spent 1 month learning it, and in that process, I created 2 libraries:
- [protoschema-go](https://github.com/Rick-Phoenix/protoschema-go), for generating protobuf files from declarative schemas written in go (with a plugin to generate ConnectRPC handlers using the same metadata extracted from those schemas).
- [querygen](https://github.com/Rick-Phoenix/querygen), which is a small helper library that generates most if not all of the boilerplate for making aggregated sqlite queries with sqlc.

And then after that, I dived into Rust, which I have really fallen in love with it. 
So after 1 month of learning it, I released my first crate: [protocheck](https://crates.io/crates/protocheck), a validation library that leverages protovalidate annotations to automatically generate validation logic in Rust.

I have also made [protoschema](https://github.com/Rick-Phoenix/protoschema), which re-implements the protoschema-go concepts in Rust, but with a much better result due to Rust's flexibility with macros. Go check that out if you work with protobuf!

## Projects and ideas for the near future
- ~Porting protoschema-go to rust (yes, I dislike writing proto files that much)~  Done, that is now [protoschema](https://github.com/Rick-Phoenix/protoschema)
- ~Including more common protobuf types in my [proto-types](https://crates.io/crates/proto-types) crate~ Done, all types from google.rpc and google.type are now supported
- Probably a few other libraries to make working with protobuf a smoother process
- Refactor a library I wrote in Typescript for generating boilerplate for TS projects, potentially porting it to Go or Rust
- Diving back into Sveltekit (which is not my frontend framework of choice) and tauri to build a desktop app
