# Reporting Template

> Author: Name Surname (<n.surname@example.com>)

## Instructions

- The content you're reading is loaded from `labX/README.md` into the labenv "Reporting" tab on every page load.
- Further changes from the UI are auto-saved to the file (overwriting any previous content)
- Press `Ctrl+P` to print this report, or manually export `README.md` using an external tool (e.g., `markdown-to-pdf` VSCode extension)
- To include an image, write `![]()` in a new block, it should prompt for the image URL (you can upload image to a sevice like [Imgur](https://imgur.com/) to get a direct link)
- This editor is using [Muya](https://github.com/marktext/muya/tree/master). It's a beta product, issues can be submitted to their repository.

## Reporting Approach

A good technical report resembles a tutorial ready to be posted on your blog.

1. Clarify used commands or scripts with short explanation.
   
   ```cpp
   #include <iostream>
   
   int main() {
       std::cout << "Hello World!";
       return 0;
   }
   ```

2. Include a screenshot of relevant results when appropriate.
   
   > You can store the image locally or use a hosted service like [Imgur](https://imgur.com/upload).
   
    ![result](https://i.imgur.com/hO0tPAb.png)

3. Be brief and concise, nobody likes reading too much text.

## Report Quality Checklist

- [x] Author name and related info on the top
- [x] Exported to a convenient format (PDF, HTML)
- [ ] Related artifacts (code, configs, binaries) are included if present.
- [ ] The file has a meaningful name.

## Extra <mark>Features</mark> for Nerds

### :chart: <u>Tables</u>

| Language | Awesomeness |
| -------- | ----------- |
| Python   | Yes         |
| Java     | No          |

### :sparkles: Math^*^~*~

$$
x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}
$$
