#Facebook Invite All

Facebook Invite All is a simple javascript Bookmarklet that allows users to select all checkboxes on a web page. This is useful when trying to invite hundreds of people to a Facebook Event.

##Try it out
Drag this link to your bookmarks bar:
(Invite All!)[javascript:void((function(){var fb=confirm('Invite All Friends Facebook Bookmarklet \n 1) Click INVITE FRIENDS on a Facebook event page \n 2) Scroll all the way to the bottom of your friends list. This ensures all your friends are loaded. \n 3) Click OK to Select all Friends, Click CANCEL to preform steps 1 and 2, then click the Bookmarklet again and click OK. \n'); if(fb){ var inputs = document.getElementsByTagName('input');for(var i=0; i < inputs.length; i++) {if(inputs[i].type == 'checkbox') {if(inputs[i].disabled == false){inputs[i].click()};}}}})());]

Please Fork!
