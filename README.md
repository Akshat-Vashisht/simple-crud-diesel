# CRUD App using Diesel

This is a simple CRUD app that uses Rust and Diesel to create a simple backend in PostgresSQL

## How to use 
1. Clone the repo
2. Make a .env file and add the following code to it
```
DATABASE_URL=postgres://<username>:<password>@localhost/<db_name >
```
4. Build the file
```
cargo build
```

## CRUD Operations 

1. Create a post
``` 
cargo run --bin write_post
```

2. Update a post (Publishing)
```
cargo run --bin publish_post <post_id>
```

3. Get a single post
```
cargo run --bin get_post <post_id>
```

4. Get all the posts
```
cargo run --bin show_posts
```

5. Delete a post
```
cargo run --bin delete_post <post_title>
```
