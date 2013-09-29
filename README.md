# App.net Buttons

Share the love, show off your followers, and allow people to discover your App.net profile. Buttons that match your other buttons. Sexy.

To get started, checkout http://adnbtns.com!


## Usage

These buttons are hosted via GitHub Pages, meaning all you need to do is include an iframe and you're set. Once included, you can configure it with various options. Here's the include:

``` html
    <iframe src="http://adnbtns.com/adn-btn.html?count=true&user=USERNAME"
  allowtransparency="true" frameborder="0" scrolling="0" width="180" height="20"></iframe>
```


### Requirements

`user`<br>
An App.net username<br>


### Optional

`count`<br>
Show the optional watchers or forks count: *none* by default or `true`

`size`<br>
Optional flag for using a larger button: *none* by default or `large`

`align`<br>
Optional flag for button alignment within iframe: *none* by default or `left` / `right` / `center`

`prefix`<br>
Optional text prepended to the username as button text. Defaults to `Follow @`

`suffix`<br>
Optional text appended to the username as button text. Defaults to the empty string.

## Examples

**Basic Follow Button**

``` html
    <iframe src="http://adnbtns.com/adn-btn.html?user=JohnONolan"
  allowtransparency="true" frameborder="0" scrolling="0" width="180" height="20"></iframe>
```

**Follow Button with Count**

``` html
    <iframe src="http://adnbtns.com/adn-btn.html?user=JohnONolan&count=true"
  allowtransparency="true" frameborder="0" scrolling="0" width="180" height="20"></iframe>
```

**Large Follow Button with Count**

``` html
   <iframe src="http://adnbtns.com/adn-btn.html?user=JohnONolan&count=true&size=large"
  allowtransparency="true" frameborder="0" scrolling="0" width="280" height="30"></iframe>
```


## Limitations

- iFrame width and height must be specificed for all buttons.
- All attributes must be passed through via URL parameters.
- CSS and javascript are all included in the same HTML file to reduce complexity and requests.

**Usage with SSL**

In order to avoid `insecure content` warnings when using GitHub Buttons on a page behind an SSL certificate, simply host a copy of the `github-btn.html` file on your secure directory and substitute your domain in the iframe include: 

``` html
    <iframe src="https://YOURDOMAIN.com/adn-btn.html?user=USERNAME"
  allowtransparency="true" frameborder="0" scrolling="0" width="100" height="20"></iframe>
```


## Bug tracker

Have a bug? Please create an issue here on GitHub at https://github.com/JohnONolan/adn-buttons/issues.


## Twitter account

Keep up to date on announcements and more by following John on App.net, <a href="http://alpha.app.net/JohnONolan">@JohnONolan</a>.


## Authors

**John O'Nolan**

* http://alpha.app.net/JohnONolan
* http://github.com/JohnONolan

Forked from the original [Unofficial Github Buttons](http://github.com/mdo/github-buttons) by Mark Otto

**Mark Otto**

* http://twitter.com/mdo
* http://github.com/mdo


## Copyright and license

Copyright 2013 John O'Nolan.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
