# Vanilla emoji Picker

> Modern emoji picker. Super light, simple and no frameworks

## Why

We needed a modern way to use emojis. Something that require almost zero effort, light and simple. That's why we created Vanilla emoji picker.

## Install

You can get it on npm.

```
npm install vanilla-emoji-picker --save
```

## Setup

First, include the scrip.

```html
<script src="node_modules/vanilla-emoji-picker/dist/emojiPicker.min.js"></script>
```

Add attribute `data-emoji-picker="true"` to any text input or textarea you want to add it

Then execute this command to initiate the plugin:

```js
new EmojiPicker();
```
## Major Changes

The attribute `data-emoji-picker="true"` will also work for div with contenteditable="true".

The attributes `top=""` and `right=""` inside the tag will provide the custom placement for the emoji picker. By default, it is 2px in case of not provided.