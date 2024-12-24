# Tailwind CSS Gradient Opacity Issue

This repository demonstrates a potential rendering issue with Tailwind CSS gradients when using opacity modifiers.  In certain situations, adding opacity to the gradient's end color might lead to unexpected visual results depending on the browser and Tailwind CSS version.

## Problem
The provided `bug.html` file shows a simple gradient. Modifying the gradient to include opacity on the second color, can lead to inconsistent rendering across different browsers or Tailwind versions.