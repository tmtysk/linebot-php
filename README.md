# linebot

a simple line bot api client. (for trial api / unofficial)

## Install

```
$ composer require cu/linebot:dev-master
```

## Usage

```
$bot = CU\LineBot("<Channel ID>", "<Channel Secret>", "<Channel MID>", "<Endpoint URL>");
$bot->isValid(); // true only if signature was valid.
$bot->sendText("<to>", "<text>"); // send text message.
$bot->postEvents($events);
```
