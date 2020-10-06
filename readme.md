To use subscribe form simply add *[wps_form]* shortcode to your post/page/temlpate.
You can add your own styles to form. Simply use this selectors:
```css
#wps__form {}
.wps__form-row {}
.wps__form-agreement {}
.wps__form-submit {}
```
Also you can use your own form with this plugin. Just send **POST** request to **/wp-json/wps/subscribe**.
Sendable data example:
```js
{
	full_name: 'John Doe',
	email: 'example@mail.com',
	gave_concent: 1
}
```
