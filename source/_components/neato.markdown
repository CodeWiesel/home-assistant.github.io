---
layout: page
title: "Neato Robotics"
description: "Instructions how to integrate your Neato within Home Assistant."
date: 2016-10-09 20:15
sidebar: true
comments: false
sharing: true
footer: true
logo: neato.png
ha_category: Hub
ha_release: 0.33
featured: true
---

The `neato` component allows you to control your [Neato Botvac Connected](https://www.neatorobotics.com/robot-vacuum/botvac-connected-series/botvac-connected/).

To enable `neato` in your installation, add the following to your `configuration.yaml` file:

```yaml
# Example configuration.yaml entry
neato:
  username: USERNAME
  password: PASSWORD
```

Configuration variables:

- **username** (*Required*): Username for the Neato account.
- **password** (*Required*): Password for the Neato account.

<p class='note'>
The Home Assistant Neato platform has only be tested with a Botvac Connected. There is no support for the Botvac D3 Connected and Botvac D5 Connected robots at this time.
</p>
