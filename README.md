# \<cc-message\>

A chat message element

## Supported Attributes

| Attribute         | Values           | Default Value |
| -------------     | -------------    | ------------- |
| author (required) | String           |               |
| receiver          | String           |               |
| mood              | String           |               |
| timestamp         | String           |               |
| is-own-message    | Boolean          | false         |


## Supported Slots

| Slot              | Children              | Description      |
| -------------     | -------------    | ------------- |
| default           | any              | The message content              |
| profilePicture    | img-tag          | Displays a image next to the message               |
| mood              | any              | Used to display a custom mood element              |


## Viewing The Element

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

```
$ polymer install && polymer serve -o
```
