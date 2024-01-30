# Web Scraping and HTTP Requests with Python's urllib

## Overview

Welcome to the Web Scraping and HTTP Requests Made Easy project! This guide explores the capabilities of
Python's `urllib` library, making web scraping and handling HTTP requests a straightforward task.

## Introduction

Python's `urllib` library provides a powerful set of tools for web interaction, enabling you to fetch data from
websites, perform HTTP requests, and more.

## Features

- **Easy Web Access:** Learn how to effortlessly make HTTP requests to websites and retrieve data.

- **Web Scraping:** Understand the basics of web scraping using `urllib` to extract information from web pages.

- **Handling HTTP Errors:** Explore how `urllib` helps you manage HTTP errors and handle different scenarios gracefully.

- **URL Parsing:** Discover the capabilities of URL parsing with `urllib` to break down URLs into meaningful components.

## Getting Started

Learn how to import `urllib` and get started with making your first HTTP requests without the need for complex setup.

## Handling HTTP Errors

Understand how `urllib` deals with HTTP errors and how to manage scenarios where the requested action is not permitted.

## URL Parsing

Explore the functionalities of `urllib` for parsing URLs, breaking them down into manageable parts.

## Contributing

Contributions to enhance and expand this guide are welcome! Feel free to open issues or create pull requests.



------------

**Running Jupyter Notebook:**

To launch the Jupyter Notebook server, use the following command:

```bash
jupyter notebook
```

(Note: Use Control-C to stop the server)

---

**Installing Dependencies:**

Ensure that the required dependencies are installed by running the following commands:

```bash
pip install -r requirements.txt
python -m pip install jupyter
```

---

**Memory Profiling:**

To profile the memory usage, decorate your Python script with `@memory_profiler.profile` and run the following command:

```bash
python -m memory_profiler main.py
```

---

**Line Profiling:**

For line-level profiling, use the `line_profiler_pycharm` package. Decorate your Python script with `@profile` and
execute the following command:

```bash
python -m line_profiler main.py.lprof > results.txt
```

Make sure to replace `main.py` with the appropriate filename.