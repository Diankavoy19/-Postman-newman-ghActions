# Postman + newman + github actions (Simple store template)

## Steps to run
1. Download this repo.
2. Run `npm i` (install node.js dependencies)
3. Run `npm run tern-on-api`(to run testing server locally )

### Overview of local server testing
Routes `/products`, `/orders` and `/users`. Below is a table of supported operations with `products` as example resource. The same operations are also supports for `orders/` and `users/`.

| VERB     |Route          | Input      | Output             |
|----------|---------------|------------|--------------------|
| GET      | /products     | *None*     | **Array**          |
| GET      | /products/:id |  **e.g 3** | **Object**         |
| POST     | /products     | **object** | **Created object** |
| PUT      | /products     | **object** | **Updated object** |
| DELETE   | /products/:id | **e.g 3**  | **Deleted object** |


4. Upload `store.postman_collection.json` in Postman app.
6. In GH action runned and saved reports of `petstore.collection.json`. For running `store.postman_collection.json` download this repo and run locally.
