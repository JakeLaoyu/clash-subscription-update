# Update Clash Subscription

> raycast extension to update clash subscription & insert custom rules

## Usage

This extension is not published to the store. So you need to clone this repo and run it locally.

```shell
git clone https://github.com/JakeLaoyu/update-clash-subscription.git
npm install
npm run dev
```

## Config

### Subscription Url

Currently, only one address is supported.

Rule: [name] | [url].

Demo:

```
V2Club | https://sub.xeton.dev
```

### Rules

Please provide a json file.

Content Demo:

```json
{
  "rules": [
    "- DOMAIN-SUFFIX,npmjs.org,🚀 节点选择",
  ]
}
```

![](metadata/scr-2.png)

### Command

![](metadata/scr-1.png)