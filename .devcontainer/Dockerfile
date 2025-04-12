# Use the official Python 3.12 slim image as the base image
FROM python:3.12-slim

# Update package lists, install build tools and git, and then clean up to reduce image size
RUN apt-get update && apt-get install -y --no-install-recommends \
    build-essential \
    git \
    && rm -rf /var/lib/apt/lists/*