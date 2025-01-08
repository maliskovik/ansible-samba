# Samba ANsible role

## Mandatory varriables
--- Nothing Mandatory ---

## Optional varriables
* samba_conf_local_dir: Local directory with ansible configs
* samba_workgroup: Samba workgroup
* samba_conf_dir: Remote samba conf.d
* samba_base_dir: Remote base samba configuration directory
* samba_server_string: Samba server string
* samba_dns_proxy: Use DNS proxy yes/no
* samaba_log_file: Location of samba logs
* samba_ldap: Use ldap true/false
* samba_ldap_server: LDAP server address
* samba_ldap_suffix: Domain base
* samba_ldap_users_suffix: Base user CN
* samba_ldap_group_suffix:  Base group CN
* samba_ldap_machine_suffix: Base machine CN
* samba_ldap_idmap_suffix: base idmap CN
* samba_ldap_admin: base admin group
* samba_ldap_ssl: use ssl on/off
* samba_includes: Listo of samba configs to includes - from samba_conf_local_dir

