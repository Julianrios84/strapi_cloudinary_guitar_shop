#  🚀 Getting started with Strapi

  
##  `Postgres - Database Tables`

**Guitar** is ***collection Type*** 
 + Collection for the registration of store items

| Attribute| Type | Basic Settings  | Advance Settings |
|--|--|--|--|
| name | text | short text | required  |
| description | rich text | - | - |
| price | number | decimal | - | - |
| picture | media | single media | image, required |
| url | uid | Attached field (name)| - |

 **Post** is ***collection Type*** 
  + Collection for registration of blog posts
 
| Attribute| Type | Basic Settings  | Advance Settings |
|--|--|--|--|
| title| text | short text | required  |
| content | rich text | - | - | 
| image | media | single media | - |
| url | uid | Attached field (title)| - |

 **Course** is ***single type*** 
 + Unique type that only accepts one input, in our case the course data 

| Attribute| Type | Basic Settings  | Advance Settings |
|--|--|--|--|
| title| text | short text | required  |
| content | rich text | - | - |
| picture | media | single media | - |
 
 
---
Strapi comes with a full featured [Command Line Interface](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html) (CLI) which lets you scaffold and manage your project in seconds.

  

###  `develop`

  

Start your Strapi application with autoReload enabled. [Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-develop)

  

```

npm run develop

# or

yarn develop

```

  

###  `start`

  

Start your Strapi application with autoReload disabled. [Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-start)

  

```

npm run start

# or

yarn start

```

  

###  `build`

  

Build your admin panel. [Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-build)

  

```

npm run build

# or

yarn build

```

  

##  ⚙️ Deployment

  

Strapi gives you many possible deployment options for your project. Find the one that suits you on the [deployment section of the documentation](https://docs.strapi.io/developer-docs/latest/setup-deployment-guides/deployment.html).

  

##  📚 Learn more

  

-  [Resource center](https://strapi.io/resource-center) - Strapi resource center.

-  [Strapi documentation](https://docs.strapi.io) - Official Strapi documentation.

-  [Strapi tutorials](https://strapi.io/tutorials) - List of tutorials made by the core team and the community.

-  [Strapi blog](https://docs.strapi.io) - Official Strapi blog containing articles made by the Strapi team and the community.

-  [Changelog](https://strapi.io/changelog) - Find out about the Strapi product updates, new features and general improvements.

  

Feel free to check out the [Strapi GitHub repository](https://github.com/strapi/strapi). Your feedback and contributions are welcome!

  

##  ✨ Community

  

-  [Discord](https://discord.strapi.io) - Come chat with the Strapi community including the core team.

-  [Forum](https://forum.strapi.io/) - Place to discuss, ask questions and find answers, show your Strapi project and get feedback or just talk with other Community members.

-  [Awesome Strapi](https://github.com/strapi/awesome-strapi) - A curated list of awesome things related to Strapi.

  

---

  

<sub>🤫 Psst! [Strapi is hiring](https://strapi.io/careers).</sub>