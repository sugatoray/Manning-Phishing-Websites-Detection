# Stage-1

GitHub does not render html files when you click on them in GitHub. While this allows you to inspect the code in a certain html file, it does not help in viewing the output. Won't it be nice to just click on an html file and see it in it's rendered form?

Well, you are not the only one to think of this feature. There is a github repository, [htmlpreview.github.com][#htmlpreview] that already takes care of this using a simple implementation.

[#htmlpreview]: https://github.com/htmlpreview/htmlpreview.github.com

All you have to do from now on is open an html file in the browser, from github and insert `https://htmlpreview.github.io/?` as a prefix to the existing URL and hit <kbd>ENTER</kbd>.

```bash
https://htmlpreview.github.io/?<URL>
```

Here are a few more examples:  

+ https://htmlpreview.github.io/?https://github.com/twbs/bootstrap/gh-pages/2.3.2/index.html
+ https://htmlpreview.github.io/?https://github.com/documentcloud/backbone/blob/master/examples/todos/index.html

---

## Viewing Reports

+ [profile_report][#profile-report]

[#profile-report]: https://htmlpreview.github.io/?https://github.com/sugatoray/Manning-Phishing-Websites-Detection/blob/master/src/stage1/profile_report.html
