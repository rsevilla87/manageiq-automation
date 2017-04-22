# ManageIQ Automation

This repository is meant to store the automation developments I make for ManageIQ and CloudForms.

## Rake tasks

Rake scripts should to be saved in the ```/var/www/miq/vmdb/lib/tasks``` directory of your appliance. All of them have usage information that could be obtained like the example below:
```
[root@e224b7f76cae vmdb]# rake config:usage
The following configuration tasks are available, arguments between [] are optional:
 List all roles available           - Usage: rake config:list_roles
 List appliance active roles        - Usage: rake config:list_active_roles [APPLIANCE_ID=appliance_id]
 Set appliance roles                - Usage: rake config:set_roles SERVER_ROLES='["roles", "json", "array"]' [APPLIANCE_ID=appliance_id]
 Summary                            - Usage: rake config:summary
 Create zone                        - Usage: rake config:create_zone NAME=zone_name DESCRIPTION=zone_description
 Modify zone                        - Usage: rake config:modify_zone APPLIANCE_ID=appliance_id ZONE_NAME=zone_name
 List appliances                    - Usage: rake config:list_appliances
 List zones                         - Usage: rake config:list_zones
```

