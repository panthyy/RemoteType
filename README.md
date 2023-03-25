![](https://media.tenor.com/dt1etVruHGAAAAAj/rylsee-tooshytorap.gif)
---
# RemoteType

RemoteType is a Language Service Plugin for TypeScript that provides advanced features like API-driven auto-completion. This powerful plugin is designed to simplify your workflow and make it easier to work with complex data structures, particularly for projects that require a CMS-powered client interface.

With RemoteType, you can quickly integrate data from any API-driven data source into your TypeScript codebase. This can be particularly useful if you're working on data-intensive web applications, where accessing and manipulating large datasets can be a cumbersome task. By leveraging RemoteType's features, you can create more intuitive and easy-to-use interfaces, without having to manually access data fields.

Some key features of RemoteType include:
  - API-driven auto-completion
  - IntelliSense support for collections
  - Support for a variety of API-driven data sources
  - Designed to enhance productivity and streamline workflow
  
## Usage

```typescript
import { RemoteType } from 'remotetype';

// Define the collection type
type UserCollection = RemoteType<"http://example.com/types/collections">;

// Use the collections function to access the "Users" collection
export const getUserCollection = (): UserCollection => {
  return collections('Users');
}

```
