# Web accessibility
> When sites are correctly designed, developed and edited, all users have equal access to information and functionality. - Wikipedia

> Accessibility is often abbreviated as the numeronym a11y, where the number 11 refers to the number of letters omitted. This parallels the abbreviations of internationalization and localization as i18n and l10n respectively. - Wikipedia

## Guideline

- Repect HTML sementic (e.g do not use a span for a button)
- Think about easy things like:
    - `<img src="" alt="image description">`
    - `<label for="username">Username</label><input id="username" />`
- Use multiple way to do things. (e.g close a modal with a cross, esc key or click away)
- Check http://www.w3.org/TR/wai-aria/
    - tabindex
    - role
    - onKeyUp

## How to test?
- [Chrome Accessibility Developer Tools](https://chrome.google.com/webstore/detail/accessibility-developer-t/fpkknkljclfencbdbgkenhalefipecmb?hl=en)
- [accesslint](http://accesslint.com/)
- [A11Y project](http://a11yproject.com/)
