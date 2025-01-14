# Golpo Svelte

This is the svelte build of the current [golpo project](https://github.com/Ananto30/golpo). Site - [golpo.dedsec.life](http://golpo.dedsec.life/)

But there are things we are changing from the current Golpo. We will use Golpo as a link sharing platform. And it will be free for eveyone! Future plan involves link management (collection of links and sorting) and sharing collection.

So here is our plan -

## Change plan

### Backend

-   Verify post is only a link.
-   Extract meta data from link and save them in the database.
-   Do not allow to share the same link in 24 hours.
-   Add like count and people who liked the post.
-   Add follow functionality.

### Frontend

-   Separate page for chats and user chat. (Chats are list of users who I have chat with in the past and UserChat is a single user chatting interface)
-   Profile edit page or modal.
-   Send message to user button and modal.

## Run the project

```
npm install
npm run dev
```

## Svelte tasks

Please note that most of the frontend data model is already there, I will add more soon.

And to get actual api response, you need to run the backend too.

Here are the tasks - [Hacktoberfest](https://github.com/Ananto30/golpo-svelte/issues?q=is%3Aissue+is%3Aopen+label%3AHacktoberfest)

(Tasks are being added daily)

**Feel free to enhance code and beautify UI** 😃
