# ShortURL

Bijective conversion between natural numbers (IDs) and short strings

Useful for URL shorteners and short IDs in your permalinks

## Usage

 * `ShortURL.encode()` takes an ID and turns it into a short string
 * `ShortURL.decode()` takes a short string and turns it into an ID

## Features
 * large alphabet (51 chars) and thus very short resulting strings
 * proof against offensive words (removed `a`, `e`, `i`, `o` and `u`)
 * unambiguous (removed `I`, `l`, `1`, `O` and `0`)

## Example output
 * `123456789` <=> `pgK8p`

## License

```
Copyright 2014 www.delight.im <info@delight.im>

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```