# React Native FlatList Performance Issue

This repository demonstrates a performance issue encountered when using FlatList in React Native with a large dataset. The app becomes sluggish and unresponsive when rendering hundreds of items.  The solution implemented addresses this performance bottleneck by using techniques to optimize rendering.

## Problem

The initial implementation renders all items at once, leading to performance problems with larger datasets.

## Solution

The solution utilizes techniques like `windowSize` and `initialNumToRender` to improve performance and manage memory better. It also showcases how to handle item updates efficiently.