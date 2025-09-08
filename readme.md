### Clone Location
GitHub disussion: https://github.com/xournalpp/xournalpp/discussions/3699  
Windows Config Folder Location: C:\Users\USER\AppData\Local\xournalpp  


### UI Scaling
GitHub Issue: https://github.com/xournalpp/xournalpp/issues/3453
Xournal++/share/xournalpp/ui/xournalpp.css
```css
/* Uncomment out and set as follows: */
toolbar button
{
	padding: 15px
}

/* Add this */
toolbar image 
{
    -gtk-icon-transform: scale(2);
}
```