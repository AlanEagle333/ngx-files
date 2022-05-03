# ngx-files
# Step 1: Installation waw-files
### Go to the waw-files in WebArtWork

# Step 2: Installation ngx-stripe
### In terminal root/client write:
waw add ngx-files
# Step 3: Import StripeModule
### In your user/page.module.ts you must import FilesModule:
import { FilesModule } from 'src/app/modules';

Don't forget to add :
@NgModule({
	imports: [
  FilesModule
  ],
# Step 4: Write Tag(files)
###  In your user/page, you must write this code:
```
<files></files>
(this tag is presented as module to upload your files)

