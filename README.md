
# Responsive Page Template

A template for making web pages that look diffrent based on device screen width.

## Device Types

- Tablet
- Phone
- Desktop


## How It Works
You write the websit code seperatly for all 3 device types, and put them into the html file. You can use the style.css file for styles that need to apply to all 3, and put styles that only apply to one device in the respective css file.
## Single Device Usage

#### Example using all h1 on desktop

```http
  .desktop h1 {
  'your style here'
  }
```

| Device | Tag     | Style                |
| :-------- | :------- | :------------------------- |
| `.desktop` | `any tag` | `any style`  |
| `.mobile` | `any tag` | `any style`  |
| `.tablet` | `any tag` | `any style`  |

#### Example using all h1 that are direct children of mobile

```http
  .mobile > h1 {
  'your style here'
  }
```

| Device | Tag     | Style                |
| :-------- | :------- | :------------------------- |
| `.desktop` | `any tag` | `any style`  |
| `.mobile` | `any tag` | `any style`  |
| `.tablet` | `any tag` | `any style`  |

## Installation

Just Clone This

```bash
  git clone https://github.com/WhyFenceCode/ResponsivePageTemplate.git
```
    
## License

[MIT](https://choosealicense.com/licenses/mit/)

MIT License

Copyright (c) 2023 WhyFenceCode

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
## Authors

- [@WhyFenceCode](https://www.github.com/WhyFenceCode)

