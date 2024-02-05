### Photo & Video
- [Affinity Photo](https://affinity.serif.com/en-us/photo/)
- [DaVinci Resolve](https://www.blackmagicdesign.com/pl/products/davinciresolve/)

### Database
- MS SQL
- [DBeaver](https://dbeaver.io/)
- MongoDB
- Redis
- ElasticSearch
- [RavenDB - ACID NoSQL Document Database](https://ravendb.net/)
- [RavenDB and Machine Learning](ravendb.net/learn/webinars/ravendb-and-machine-learning)
- [Marten - .NET Transactional Document DB and Event Store on PostgreSQL](https://martendb.io/) 
- InfluxDB
- PostgreSQL
- tspdb [prerequisites](https://tspdb.mit.edu/installation/#prerequisites-postgresql-and-plpython_1)
- cosmos db emulator
- EF core 

### Message Broker
 - Kafka (+ ActiveMQ, Solice) 
 - RabbitMQ via [EasyNetQ](https://easynetq.com/), [MassTransit](https://masstransit-project.com)
 - Azure Service Bus
 - webspheremq

### Libs
 - Swagger
 - [Scrutor](https://github.com/khellang/Scrutor)
 - [Flurl](https://flurl.dev/)
 - AutoMapper
 - RestSharp, [Refit](https://github.com/reactiveui/refit)

 
### Docker, 
 - Kubernetess, k3s
 - terraform - longhorn
 - Rancher - container management platform
 - Portainer: Container Management

### Test
 - FluentAssertions
 - NSubstitute
 - Moq 
 - FakeItEasy
 - AutoFixture
 - XUnit 
 - NUnit 
 - MSTest 2
 - Selenium, 
 - Playwright `pwsh bin\Debug\netX\playwright.ps1 install`
 
 ### Azure
- Azure WebApp
- Azue Media Services
- Event Grid
- Storage

### .Net
- https://benfoster.io/blog/mvc-to-minimal-apis-aspnet-6/
- [record](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/record)
- [property pattern](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/operators/patterns#property-pattern)
- [serilog](https://github.com/datalust/dotnet6-serilog-example)
- [OpenStack](https://github.com/openstacknetsdk/openstack.net/wiki/Getting-Started-With-The-OpenStack-NET-SDK)
- [OpenStack - ObjectStorage](https://github.com/openstacknetsdk/openstack.net/blob/master/src/Samples/CSharpCodeSamples/ObjectStorageProviderExamples.cs)
- [File Upload in ASP.NET Core MVC](https://code-maze.com/file-upload-aspnetcore-mvc/)
- [Login - Jwt. Identity, Facebook](https://fullstackmark.com/post/13/jwt-authentication-with-aspnet-core-2-web-api-angular-5-net-core-identity-and-facebook-login)
- [SimplCommerce](https://github.com/simplcommerce/SimplCommerce/blob/master/src/Modules/SimplCommerce.Module.Orders/Services/OrderService.cs)
- https://benfoster.io/blog/mvc-to-minimal-apis-aspnet-6/

### .Net Testing
- [integration tests in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/test/integration-tests?view=aspnetcore-5.0)
- [Unit test controller logic in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/mvc/controllers/testing?view=aspnetcore-6.0)
- [How to test your C# Web API](https://timdeschryver.dev/blog/how-to-test-your-csharp-web-api#a-simple-test)
- https://blog.elmah.io/moq-vs-nsubstitute-vs-fakeiteasy-which-one-to-choose/
- https://lee-jdale.medium.com/testing-in-net-with-webapplicationfactory-including-minimal-apis-ddcb4ed0aef5

#### Serializers
##### Complex class

| Syntax | Time [ms] | Size [bytes] |
| --- | ----------- |----------- |
| [Binary Formatter](https://github.com/dotnet/standard/System.Runtime.Serialization.Formatters.Binary.cs) | 4282 |1400 |
| [NetSerializer](https://github.com/tomba/netserializer) | 204 |106 |
| [SimpleBinaryEncoding](https://github.com/real-logic/simple-binary-encoding) | 727 |58 |

##### POCO

| Syntax | Time [ms] | Size [bytes] |
| --- | ----------- |----------- |
| [Binary Formatter](https://github.com/dotnet/standard/System.Runtime.Serialization.Formatters.Binary.cs) | 3829 |1132 |
| [NetSerializer](https://github.com/tomba/netserializer) | 115 |18 |
| [MessagePack](https://github.com/neuecc/MessagePack-CSharp) | 463 |46 |


#### API Gateway
- [Azure API management](https://azure.microsoft.com/en-us/services/api-management)
- [kong](https://konghq.com/kong/)
- [ambasador](https://www.getambassador.io/)
- [ocelot](https://github.com/ThreeMammals/Ocelot)
- [Deploying NGINX as an API Gateway](https://www.nginx.com/resources/library/nginx-api-gateway-deployment)

### DevOps
 - [ASP.NET on linux](https://www.meziantou.net/publishing-an-asp-net-core-website-to-a-linux-host.htm)
 - [Terraform](https://www.terraform.io/)
 - [Pulumi](https://www.pulumi.com/)
 - Kubernetes
 - [Monitoring - Fluentbit](https://docs.fluentbit.io/manual/administration/monitoring)
 - [ELK Elastic Search Lostash Kibana](https://www.elastic.co/what-is/elk-stack)
 - [RDP Manager](https://remotedesktopmanager.com/)
### UI Design
- [Account Settings](https://dribbble.com/shots/5434357-Profile-Page-UI-Design)
- [Contact us Feedback](https://dribbble.com/shots/6500013-Message-Delivery-Confirmation-UI-Design)

### JavaScript, TypeScript, HTML5, CSS3/LESS/SCSS
- Angular RxJs
- React/Next.js [ISG](https://nextjs.org/docs/basic-features/data-fetching/incremental-static-regeneration)
- Node.js/NestJs
- Flutter
- Meteor
- GraphQ [Hasura](https://hasura.io/), [Apollo] (https://www.apollographql.com/docs/react/data/subscriptions/)
- axios, fetch - http client
- prisma - ORM
- Bootstrap, Material UI, Semantic-UI, Tailwind, Styled-Components
- Saleor/Medusa, Strapi

### JavaScript Test
 - Jest, 
 - Cypress
 - Nightmare
 - Protractor - end-to-end test framework for Angular
 - Jasmine/Karma ( Angular test runner) -> Jest (replaces Karma)

### Documentation
 - [docsify](https://docsify.js.org/)

### CMS
 - [Strapi](https://strapi.io/)
 - [directus](https://directus.io/)
 - [Storyblok](https://www.storyblok.com/)
 - [DatoCMS](https://www.datocms.com/)
 - [Sanity](https://www.sanity.io/)
 - [Prismic](https://prismic.io/)
 - [Netlify cms](https://www.netlifycms.org/)
 - [Contentful](https://www.contentful.com/)
 - [Buttercms](https://buttercms.com/)

### CMS - e-commerce
- Saleor - https://saleor.io/blog/combining-headless-architectures-with-saleor-and-strapi-147/
- Medusa

### CSS Animation Libraries CSS/SCSS/Less
- [animista](https://animista.net/)
- [animate](https://animate.style/)
- [css animation](http://cssanimation.io/)

### S3 Object Storage
- [Minio](https://min.io/)
- [OpenStack.NetSwiftClient](https://github.com/JeanCollas/OpenStack.NetSwiftClient)
- [ovh/csharp-ovh](https://github.com/ovh/csharp-ovh)
- [node ovh objectstorage](https://github.com/dimer47/node-ovh-objectstorage)

### React
 - https://github.com/sergiodxa/remix-utils
 - https://github.com/plouc/nivo - dataviz components
 - https://github.com/potree/potree - WebGL point cloud viewer for large datasets

### Bootstrap
 - https://freefrontend.com/bootstrap-code-examples/

### Projects & Tools
- [DNC-DShop](https://github.com/devmentors/DNC-DShop)
- [discourse](https://github.com/discourse/discourse)
- https://react.semantic-ui.com/

### Web technologies: Angular, RxJs, React, Next.js, Node.js, NestJs, Strapi, Saleor, 
### CSS3/LESS/SCSS, GraphQ, Bootstrap, Material UI, Tailwind, Styled-Components, Semantic UI

```
npm install --save bson 
import { ObjectID } from 'bson';
const id  = new ObjectID(); 
console.log(id.toString()); 
```

```
npm config set proxy http://proxy.pl:80/
npm config set https-proxy http://proxy.pl:80/
npm config set strict-ssl false
```

```
setx PATH "c:\edb\languagepack\v1\Python-3.7;%PATH%"
setx PATH "c:\Program Files\PostgreSQL\12\bin;%PATH%"
setx PATH "c:\edb\languagepack\v1\Python-3.7\Scripts;%PATH%"

setx PYTHONHOME "c:\edb\languagepack\v1\Python-3.7"
COPY 

"c:\edb\languagepack\v1\Python-3.7\python37.dll"
"c:\Windows\System32\python37.dll"
```

```
New-EventLog -LogName Application -Source "APPNAME"

sc.exe delete AppNAME
sc.exe create AppNAME binpath= "D:\App.exe" start= auto

CAST(([AskTimestampUtcTicks] - 599266080000000000) / 10000000 / 24 / 60 / 60 AS datetime) as TimeDay
```

```
ArgumentNullException.ThrowIfNull();

JsonConvert.DeserializeObject<MyClass>(await response.Content.ReadAsStringAsync())
```

```
var items = [].Select(i => i).ToList();
var items = [].ConvertAll(i => i);
```

```
import * as React from "react";
import { ClientTest } from "~/components/chart.client"; //components/chart.client.tsx

export default function Index() {
  const [mounted, setMounted] = React.useState(false);
  React.useEffect(() => {
    setMounted(true);
  }, []);
  return <div className="remix__page">{mounted ? <ClientTest /> : null}</div>;
}

<link rel="import" type="application/json" href="users2.json" />


<Suspense fallback={<Loading/>}>
    <Component data={data}/>
</Suspense>


import posts from '../../posts.json'

const Post = props => {
  return (
    <div>
      <h1>{props.post.title}</h1>
      <p>Published on {props.date}</p>
      <p>{props.post.content}</p>
    </div>
  )
}

Post.getInitialProps = async ({ query }) => {
  const moment = (await import('moment')).default()
  return {
    date: moment.format('dddd D MMMM YYYY'),
    post: posts[query.id]
  }
}

export default Post

```

### buzzwords
Micro-service oriented programming skills
DDD, Clean Code, SOLID, TDD, CQRS
MACH principle (Microservice-based, API-first, Cloud-native, and Headless)
Design Patterns, Agile/ Scrum and Kanban
sklepiko.com

### E-commerce
product
category
discount
order (details + items)
user
shipping details
payment details
cart items

Carts
Customers
Checkout
Discounts
Orders
Products
Reporting
Storefront
Subscription
Developers
RefreshTokens
Users
B2C	
Multi-store	
Multi-vendor marketplace		
B2B
Admin users
Role-based permissions
Multi-currency
Guest checkout
Manual order creation
Post-sale order editing
Coupons
Gift cards
Abandoned cart recovery
Storewide promotions & discount rules
Bulk coupon generation
Saved credit cards
Payment processing with Stripe, PayPal, Amazon Pay
Standard products
Subscription products
Options per product
Variants per product
Categories & sub-categories
Custom product attributes
Variant-specific images
Cross-sells & upsells
Stock inventory and history
Product bundling
Bulk price rules
Shipping price rules
International pricing
backend API
Headless storefront
Self-hosted storefronts
Visual theme editor
Drag & drop menu editor
Hosted checkout
Checkout API
Webhooks
Media CDN with image transforms



### CandlesStick patterns
- Money Flow Index (MFI)
- Stochastic Relative Strenth Index (RSI)
- Commodity Channel Index (CCI)
- Moving Average Convergence Divergence (MACD)
- Volume & Volume Weigheted Average Price (VWAP)
- Candle Stick Patterns by Weight
