# Show Unique Platforms

## Description

Find unique Vendor, Model, OS combinations in a network snapshot

## Query

```
{
  devices{
    platform{
      vendor
      model
      osVersion
    }
  }
}
```

## Python Script
[Show Unique Platforms](show_unique_platforms.py)