# ISpeak

**ISpeak** - is an innovative approach in social networking that utilizes a power of Web3 to provide an unlimited unrestricted communication.

<br />

## Version 1.0.0 Roadmap.

- [ ] Add Media storage system for images and video. Media should be served statically and later be optimized using CDN;
- [ ] Add W3 interaction interface (wallet authorization, transactions);
- [ ] Add DB full-text search functionality to be later used with **Posts** and **Replies**;
- [ ] Add **Users** associated with a crypto wallet (probably MetaMask);
- [ ] Add **Posts** that could have text and multimedia content (image or video);
- [ ] Add **Replies** that could only have (plain text/md) content, and has to be associated with a **Post**;
- [ ] Add **Likes**;
- [ ] **Posts**, **Replies** and **Likes** should implement W3 compatible interfaces to be stored on chain;
- [ ] Implement basic UI to manipulate user's data (posts, replies, likes) and to view content (feed, search);

<br >

## Notes.

- [postgres](https://rust-lang-nursery.github.io/rust-cookbook/database/postgres.html) and [full-text search](https://www.postgresql.org/docs/current/textsearch.html);
- [env](https://rust-lang-nursery.github.io/rust-cookbook/database/postgres.html);
- [http](https://doc.rust-lang.org/book/ch20-00-final-project-a-web-server.html) & [api](https://dev.to/deciduously/oops-i-did-it-againi-made-a-rust-web-api-and-it-was-not-that-difficult-3kk8);
- [static serving](https://docs.rs/hyper-staticfile/latest/hyper_staticfile/);
- [websocket](https://docs.rs/websocket/latest/websocket/);
- [w3](https://tms-dev-blog.com/rust-web3-connect-to-ethereum/), [smart contracts](https://docs.near.org/docs/develop/contracts/rust/intro), [ethereum](https://ethereum.org/en/developers/docs/programming-languages/rust/) + [tutorial](https://coinsbench.com/ethereum-with-rust-tutorial-part-1-create-simple-transactions-with-rust-26d365a7ea93);