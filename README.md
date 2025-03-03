# README: Data Overview

## Overview
This document provides an overview of three Excel files that contain data related to user highlights, testimonials, and general user information.

## Files Explained

### 1. Highlights (`highlights_updated.xlsx`)
- **Description**: This file contains records of images uploaded by users, along with the people tagged in those pictures.
- **Columns**:
  - `Timestamp`: The date and time when the image was uploaded.
  - `Uploader`: The user who uploaded the image.
  - `Tag 1` to `Tag 106`: Users who were tagged in the picture.

### 2. Testimonials (`testimonials_analyzed.xlsx`)
- **Description**: This dataset consists of testimonials written by users for other users, along with metadata such as reactions and sentiment analysis.
- **Columns**:
  - `Receiver`: The user receiving the testimonial.
  - `Writer`: The user who wrote the testimonial.
  - `Approved`: Indicates whether the testimonial has been approved.
  - `Timestamp`: When the testimonial was recorded.
  - `Reaction_0` to `Reaction_5`: Reactions given by users.
  - `Positive Score`, `Neutral Score`, `Negative Score`: Sentiment analysis of the testimonial.
  - `Character Length`, `Word Count`, `Emoji Count`, `Emojis Used`: Linguistic features of the testimonial.

### 3. Users (`users.xlsx`)
- **Description**: Contains basic user data.
- **Columns**:
  - `CreatedAt`: The timestamp of user account creation.
  - `Username`: Unique identifier for each user.

## Notes
- There are cases where testimonials have been written twice.
- Duplicate highlights may exist and need to be identified.
- There are cases where the testimonial has been written / rewritten using chatgpt. 
