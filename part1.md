# White House News Analysis Project Part 1

## Web Scraping

The internet is a huge place, with so much useful data at our fingertips. In fact, there's so much data on the web that sometimes it is difficult for humans to easily access and make sense of the data.

**Web scraping** programs are scripts that access the web and extract data from websites. We can then use these data for many different things (analysis, visualization, etc).

### HTTP and `requests`

When we access a webpage in a web browser, the browser uses **HTTP** (Hypertext Transfer Protocol) to transfer information from web servers to your computer.

In Python, the `requests` library can be used to send HTTP requests. To install `requests`, use this command in your terminal.

```
pip install requests
```

### HTML Parsing and `Beautiful Soup`

Using HTTP, we can get the HTML (HyperText Markup Language) source code of a webpage. But HTML can also be very tedious for humans to read.

Luckily, the Python package `Beautiful Soup` can parse messy HTML so we can  easily extract the data we need.

Here's the command to installing `Beautiful Soup`.

```
pip install beautifulsoup4
```
