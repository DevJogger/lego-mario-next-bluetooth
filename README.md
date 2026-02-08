## Overview

This project demonstrates how to use the Web Bluetooth API from a browser to connect to a LEGO Mario device and explore its sensors and capabilities. It is a small Next.js app with example pages for different sensor experiments (for example, color sensing and IMU experiments).

Use this repository as a reference or starting point for building browser-based Bluetooth interactions with LEGO Powered Up / LEGO Mario-type devices.

## Features

- Connect to a LEGO Mario device using the browser's Web Bluetooth API
- Example experiments: color sensor page, IMU sensor page
- Minimal Next.js UI to initiate pairing and display sensor readings

## Requirements

- Node.js (16+ recommended)
- A Chromium-based browser with Web Bluetooth support (Chrome, Edge) or other browsers that support the Web Bluetooth API
- Bluetooth hardware and a LEGO Mario or compatible LEGO Powered Up hub

Note: Web Bluetooth works only in secure contexts (HTTPS) or on `localhost`. On macOS, Chrome supports Web Bluetooth; Safari support is limited.
