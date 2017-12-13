### Unreleased

### 0.6.2 2017/12/13
- Update .gitignore
- Add two-step verification to signin

### 0.6.1 2017/10/23 
- Replace twreporter-react-components by @twreporter/react-article-components

### 0.6.0 2017/10/11
- Use npm-scope. Rename twreporter-keystone to @twreporter/keystone

### 0.5.37 2017/10/02
- Add two more position between title and leading image 

### 0.5.36 2017/09/21
- Pass filetype and filename to resize function while resizing gcsimage and gcsimages

### 0.5.35 2017/08/25
- Rebuild the package

### 0.5.34 2017/08/24
- Bug fix. Date will turn back to the first value after modifying other fields

### 0.5.33 2017/08/24
- Multiline for input of image description 

### 0.5.32 2017/03/20
- [Update] Add relatedsForamt and titlePosition types for multiple styles of topics

### 0.5.29 2016/11/24
- [Update] Use http://keystone-preview.twreporter.org to render preview article page

### 0.5.27 2016/11/24
- [Update] Use keystone-preview.twreporter.org to render preview article page

### 0.5.26 2016/10/28
- [Update] Set max-age of cache-control header to one year for uploading images and files onto google cloud storage

### 0.5.25 2016/10/11
- [Add] Preview button and preview column for linking to preview page

### 0.5.24 2016/10/7
- [Add] use http-proxy to proxy preview article page request to other server

### 0.5.23 2016/09/13
- Add Cache-Control for uploading images and audios onto GCS(a week)  

### 0.5.22 2016/09/01
- Bug fix. Store ordered-list and unordered-list in the right way

### 0.5.21 2016/08/30
- Workaround for using twreporter-react pkg without error

### 0.5.20 2016/08/29
- Increase slide limitation of Slideshow

### 0.5.19 2016/08/24
- Enable to copy & paste HTML on the editor of entity editing block.
- Enable to insert soft newline on the editor of entity editing block.

### 0.5.18 2016/08/24
- Insert soft new line by typing `ctrl` or `shift` and `enter` keys

### 0.5.17 2016/08/23
- Fix Datetime and Date issue.

### 0.5.16 2016/08/23
- Render Embedded Component well while embedded code is iframe
- Get height and width of iframe if provided for Embedded component

### 0.5.15 2016/08/19
- Use wordaround to delete the last item of relationship field
- Make Embedded and ImageLink component alignable
- Put Link button back to the editor of InfoBox and Annotation

### 0.5.14 2016/08/18
- Fix bug. Annotation works abnormally

### 0.5.13 2016/08/17
- Bug fix. Render ImageLink by Embedded Component.
- Add target="_blank" attribute when converting LINK entity into a tag

### 0.5.11 2016/08/17
- Bug fix. Import lodash.

### 0.5.10 2016/08/16
- Bug fix. Import twreporter-react pkg in the right path.

### 0.5.9 2016/08/16
- Add default blockquote block type of draftjs back

### 0.5.7 2016/08/16
- Fix Infogram embedded script bug, also handle embedded code with script tags.

### 0.5.6 2016/08/15
- Add ImageLink component, which makes editor input image url and get image html tag output

### 0.5.5 2016/08/14
- Back compatible with old data whose entity type might be lower case

### 0.5.4 2016/08/14
- Handle pasted text
- take off h3 to h6 of the Draft Editor

### 0.5.3 2016/08/13
- Fix image uploading bug.

### 0.5.2 2016/0813
- Delete local temporary files synchronously
- render image-collection listing page efficiently

### 0.5.1 2016/08/12
- Delete local temporary files after uploding images

### 0.5.0 2016/08/03
- Replace pkg react-article-components by twreporter-react
- Upgrade React to 15

### 0.4.16 2016/07/20
- Fix bug. Fix the problem we cannot change the images in the Slideshow component.
- Make ImageDiff component editable.

### 0.4.15
- Integrate Youtube and BlockQuote component of react-article-components
- Draft editor style tunning

### 0.4.14
- Integrate slideshow component of react-article-components

### 0.4.13
- Bug fix; search images by keyword
- Style change; add select icon and remove icon
