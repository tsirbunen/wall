 <style>
.container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    background-color: black;
    border-radius: 30px;
    color: orange;
}
.title {
    color: orange;
    margin-top: 20px;
    margin-bottom: -20px;
}
.title-info {
    color: orange;
    margin-bottom: 20px;
}
</style>  

<div class="container">
    <h1 class="title">
        WALL
    </h1>
    <h4 class="title-info">
        framing challenges as opportunities online
    </h4>
</div>

### What is the WALL?
Wall is an application that enables practising the **HMW (how might we) technique** collaboratively online. Both desktop and mobile will be supported.
If you are unfamiliar with the technique, have a look at **[this short introduction to HMW](https://medium.com/pm101/how-might-we-learn-about-this-framework-2add572be3d5)** by Thaisa Fernandes.  

### Architecture
This project is very much about becoming more fluent with Amazon Web Services, but also to improve my React/Typescript and Flutter skills. The WALL will be a **serverless** application, and it will consist of AWS-supplied building blocs and services wherever feasible:
- **Cognito**: authentication
- **React, Amplify SDK and Apollo Client**: web app
- **Flutter**: mobile app
- **AppSync**: full management of serverless implementation of GraphQL, integration to DynamoDB
- **Apache VTL**: GraphQL resolvers
- **DynamoDB**: persistent data storage






