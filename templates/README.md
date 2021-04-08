The template files.

The name without the file extension is the name of the template to put in the Google Sheet under siteinfo - template.

## Templates

- default: clean listing template. Uses Bulma CSS 
- default_cards: clean card layout. Uses Bulma CSS
- shop: minimalistic shop frontend using Tailwind CSS


## Templating System

Spreadsheet2site uses html/template from GO. The template syntax is straightforward.

### Access Sheet Values aka Objects

- Items: list of all items (items tab in sheet; each row becomes an item object
- Name: name of the site (siteinfo tab - name field)
- Description: name of the site (siteinfo tab - description field)
- Meta.*: access all fields by name of the siteinfo tab. (First letter is always capatilzed, e.g. slogan = Slogan)
- NavItems: list of navitems (navigation tab), each with a URL (column B) and Name (column A)

#### Item Object

Row #2 in the spreadsheet defines the column names. Column names shall only conaint latin alphabet a to z, lower and uppercase. The first eltter of a column name is always capatilized.

name -> Name
shortDecription -> ShortDescription