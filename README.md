You can always access the archives of the Referèndum 2017 site by visiting https://gateway.ipfs.io/ipns/QmZxWEBJBVkGDGaKdYPQUXX4KC5TCWbvuR4iYZrTML8XCR/

You can also help in seeding the contents or you can visit the page on your own machine following these instructions:

- Download and extract the latest IPFS binaries into your folder of choice: https://dist.ipfs.io/#go-ipfs
- Then open a terminal, point it to the folder you extracted IPFS into and execute these:

```sh
./ipfs init
./ipfs daemon
```

- *This might take some time... Go grab a nice coffee or tea or get some sleep while it is running.* Open another terminal while leaving the previous running and execute these:

```sh
./ipfs get $(./ipfs resolve -r /ipns/QmZxWEBJBVkGDGaKdYPQUXX4KC5TCWbvuR4iYZrTML8XCR)
```

- After getting all data succeeded (about 2GB of content) you can visit the page locally: https://localhost:8080/ipns/QmZxWEBJBVkGDGaKdYPQUXX4KC5TCWbvuR4iYZrTML8XCR/

Enjoy and thanks for sharing and caring. 
