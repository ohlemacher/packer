<!-- Code generated from the comments of the Config struct in builder/vsphere/iso/config.go; DO NOT EDIT MANUALLY -->

-   `create_snapshot` (bool) - Create a snapshot when set to `true`, so the VM can be used as a base
    for linked clones. Defaults to `false`.
    
-   `convert_to_template` (bool) - Convert VM to a template. Defaults to `false`.
    
-   `export` (\*common.ExportConfig) - Configuration for exporting VM to an ovf file.
    The VM will not be exported if no [Export Configuration](#export-configuration) is specified.
    