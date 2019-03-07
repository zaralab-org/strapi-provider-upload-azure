# strapi-provider-upload-azure

## Resources

Migrated to 3.0.0-alpha.24.1

includes image thumb resize that appends 'thumb-' to the same file, private and public blob container management, and private and public files download function (that you should manualy implement inside strapi)
Because of the download function, file size is being stored in DB in bytes, thus showing much larger file sizes, than the actual, inside the admin panel (of course if you do not patch it).

Custom paths can be used also, just pass the path parameter to the js SDK :)

Can be used with a Azure CDN, just provide the CDN name and all hyperlinks will be automaticaly resolved to the CDN instead of the blob container

