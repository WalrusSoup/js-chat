> [!IMPORTANT]  
> Pubnub moved their Javascript Chat SDK to Kotlin and, to be honest, I am not sure how that works at all. But I do know that my bugs left unfixed for several months,
> so I just decided to start fixing it myself.

# PubNub JavaScript Chat SDK

Chat SDK offers a set of handy methods to create your own feature-rich chat or add a chat to your existing application.

## Supported platforms

Chat SDK is written in TypeScript and relies on the existing [JavaScript SDK](https://www.pubnub.com/docs/sdks/javascript).

It's framework-agnostic and lets you build client-side or server-side chat apps using any JavaScript-based framework, like:

- React
- React Native
- Vue
- Angular
- Nest
- Express

## Features

Chat SDK offers a wide range of features to build direct, group, and public chats.

Explore these documentation sections for details:

- **Channels** - manage [channels](https://www.pubnub.com/docs/chat/chat-sdk/build/features/channels/create), [join](https://www.pubnub.com/docs/chat/chat-sdk/build/features/channels/join) or [leave](https://www.pubnub.com/docs/chat/chat-sdk/build/features/channels/leave) them, [invite](https://www.pubnub.com/docs/chat/chat-sdk/build/features/channels/invite) other chat members, or [reference channel names](https://www.pubnub.com/docs/chat/chat-sdk/build/features/channels/references) in messages through hashtags.
- **Users** - manage [users](https://www.pubnub.com/docs/chat/chat-sdk/build/features/users/create), track user's [presence](https://www.pubnub.com/docs/chat/chat-sdk/build/features/users/presence), [mention](https://www.pubnub.com/docs/chat/chat-sdk/build/features/users/mentions) users, manage [permissions](https://www.pubnub.com/docs/chat/chat-sdk/build/features/users/permissions) or [report](https://www.pubnub.com/docs/chat/chat-sdk/build/features/users/moderation) users for misbehaving.
- **Messages** - manage [messages](https://www.pubnub.com/docs/chat/chat-sdk/build/features/messages/send-receive), add [reactions](https://www.pubnub.com/docs/chat/chat-sdk/build/features/messages/reactions), [forward](https://www.pubnub.com/docs/chat/chat-sdk/build/features/messages/forward) messages to others, [pin](https://www.pubnub.com/docs/chat/chat-sdk/build/features/messages/pinned) them to channels, add [quotes](https://www.pubnub.com/docs/chat/chat-sdk/build/features/messages/quotes) or [links](https://www.pubnub.com/docs/chat/chat-sdk/build/features/messages/links), create [threads](https://www.pubnub.com/docs/chat/chat-sdk/build/features/messages/threads) or send [files](https://www.pubnub.com/docs/chat/chat-sdk/build/features/messages/files), [report](https://www.pubnub.com/docs/chat/chat-sdk/build/features/messages/moderation) offensive messages, or shows users how many messages they missed while they were offline through [unread messages](https://www.pubnub.com/docs/chat/chat-sdk/build/features/messages/unread).

Also, add [typing indicators](https://www.pubnub.com/docs/chat/chat-sdk/build/features/typing-indicator), [push notifications](https://www.pubnub.com/docs/chat/chat-sdk/build/features/push-notifications), and more.

## Samples

Test our sample Chat SDK apps created in various frameworks:

| Source code                                                                                                      | Framework    | Description                                                                                                                                                                                                                                                                                                         |
| :--------------------------------------------------------------------------------------------------------------- | :----------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Direct chat](https://github.com/pubnub/js-chat/blob/master/samples/getting-started/README.md)                   | React        | Basic 1:1 support chat letting you exchange messages between a user and a support agent.                                                                                                                                                                                                                            |
| [Group chat](https://github.com/pubnub/js-chat/blob/master/samples/react-native-group-chat/README.md)            | React Native | Feature-full group chat letting you test most of the features offered by the Chat SDK.                                                                                                                                                                                                                              |
| [Access Manager API service](https://github.com/pubnub/js-chat/blob/master/samples/access-manager-api/README.md) | NestJS       | Backend service creating an authentication key endpoint for users, integrated with PubNub's Chat SDK to generate Access Manager authentication tokens with appropriate permissions. It allows for controlled access to all channels and reflects user-specific restrictions, with tokens expiring after 15 minutes. |

## Chat SDK docs

You'll find all the information about working with Chat SDK in the official [PubNub Chat SDK documentation](https://www.pubnub.com/docs/chat/chat-sdk/overview).
