<!-- Code generated from the comments of the Config struct in builder/yandex/config.go; DO NOT EDIT MANUALLY -->

-   `folder_id` (string) - The folder ID that will be used to launch instances and store images.
    Alternatively you may set value by environment variable YC_FOLDER_ID.
    
-   `token` (string) - OAuth token to use to authenticate to Yandex.Cloud. Alternatively you may set
    value by environment variable YC_TOKEN.
    
-   `source_image_family` (string) - The source image family to create the new image
    from. You can also specify source_image_id instead. Just one of a source_image_id or
    source_image_family must be specified. Example: ubuntu-1804-lts
    