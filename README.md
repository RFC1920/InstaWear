# InstaWear - Rust Plugin for Oxide

InstaWear is an Oxide plugin for Rust. It enables players to wear picked up clothing directly without needing to drag them onto their character manually.

## Features

    Automatic Clothing Equipping: Players automatically wear clothing items when picked up.
    Permission System: Optionally, enforce the instawear.use permission for using InstaWear.

There are no commands or configurations needed for InstaWear. Simply pick up clothing items, and they will be worn automatically.


## Permissions
  - instawear.use - Allows players to use InstaWear to automatically wear clothing items.

## Configuration

```json
{
  "RequirePermission": false,
  "Version": {
    "Major": 0,
    "Minor": 0,
    "Patch": 1
  }
}
```

 - RequirePermission - If true, users must have the instawear.use permission
