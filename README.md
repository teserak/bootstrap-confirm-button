Bootstrap Confirm Button
============

A simple button to comfirm a task.
Instead of using rude modals that interrupt a user's workflow, let's use a inline unobtrusive button instead.
Designed especially for devices with small screen. 

**Compatible with Bootstrap 3!**

*Ispired by: http://eli.eliandlyndi.com/2011/10/10/using-jquery-to-provide-an-inline-confirmation-on-buttons/*


 #usage:


```html

<a class="btn btn-primary btn-delete-item">Delete</a>

```

```javascript

$('.btn-delete-item').btsConfirmButton("I'm sure!", function(e) {
	console.log('Item deleted!');
});
```

**advanced configuration:**

```javascript
$('.btn-delete-item').btsConfirmButton({
		msg: "Confirm Deletion",
		timeout: 3000,
		className: 'btn-danger'
	}, function(e) {
	console.log('Item deleted!');
});

```

![Image](https://raw.githubusercontent.com/stefanocudini/bootstrap-confirm-button/master/confirm-delete-button.png)

Example:
------
[Example](example.html)

Source code:
------

[Github](https://github.com/stefanocudini/bootstrap-confirm-button)
[NPM](https://npmjs.org/package/bootstrap-confirm-button)  
[Atmosphere](https://atmosphere.meteor.com/package/bootstrap-confirm-button)
