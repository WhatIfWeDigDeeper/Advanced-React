# GraphQL

- [GitHub Repo](https://github.com/wesbos/Advanced-React/)
- standard for requesting data
- does not include filtering, sorting

## playground

- double quotes on values with prisma

[Sample data](https://us1.prisma.sh/wesbos/sick-fits/dev)

```graphql
query {
  items {
    id
    title
    user {
      name
      email
      cart {
        item {
          title
        }
      }
    }
  }
}
```

## [Prisma](https://www.prisma.io)

### [Setup local new db using Docker](https://www.prisma.io/docs/get-started/01-setting-up-prisma-new-database-JAVASCRIPT-a002/)

[local admin](http://localhost:4466/_admin)

[Prisma VSC extension](https://marketplace.visualstudio.com/items?itemName=Prisma.vscode-graphql)

[left off at](https://courses.wesbos.com/account/access/5bfc0c23256ae9346111ef19/view/289537335)

### Cloudinary

1. go to your settings and turn on unsigned uploading
