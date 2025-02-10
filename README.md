
# Curry Brand Limited Edition Design Project 🏀👟

## Project Overview
Generate unique, eye-catching designs for a Curry Brand limited edition basketball shoe using AI image generation. The goal is to create visually striking iterations that stand out in social media feeds and convey the exclusivity of a signature shoe from one of basketball's greatest players.

## Objectives
- Transform existing Curry Brand shoes into distinctive limited editions
- Create designs that capture immediate attention in social feeds
- Maintain brand authenticity while pushing creative boundaries


# API Reference

## Stability ai API key

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

# Prerequisites

1. Stability ai API key
2. An image to be used as input
# Workflow
![Image](https://github.com/user-attachments/assets/3b8dcd54-83db-4bda-9951-c392016a2936)
# Technical Implementation Steps
## Notebook Setup and Configuration

## 1. Library Imports

- Import necessary Python libraries for API interactions, image processing, and visualization
- Ensure compatibility with Stability AI image generation requirements


## 2. API Configuration

- Declare Stability AI API key securely
- Set Stability base URL for API endpoints
- Define specific API endpoints for image generation functionality
- Configure request headers for authentication and content type


## 3. Core Functions

- make_control_structure(): Create image generation control parameters

  - Define input image transformations
  - Set up generation constraints
  - Prepare design iteration parameters


- save_image(): Utility function for result image storage

  - Handle file naming conventions
  - Ensure high-quality image preservation
  - Organize generated designs systematically




## 4. Image Generation Workflow

- Invoke make_control_structure() with Curry shoe base design
- Generate multiple design variations
- Save each iteration using save_image() function


## 5. Visualization and Validation

- Display generated shoe designs
- Compare iterations against project objectives
- Select most promising concepts for further refinement
## Example
![Image](https://github.com/user-attachments/assets/9f70939d-af92-48fd-9bfb-980c9e27d6e7)