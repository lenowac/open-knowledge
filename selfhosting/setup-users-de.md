# Users
20210328202918

- root user hat keine admin rechte
- es gibt ein sudo account, jedoch nicht unter root/admin/klarnamen

Warum? Vermeidung von brute force: es muss nun username und passwort geknackt werden.

## root : whats in the folders
ideally nothing.

## _ : whats in the folders

~/configuration
*(git repo with all config files, subfolders symlink to respective locations)*

~/development 
*(for testing out stuff, e.g.: LXC containers)*
	/ynh-dev --> YunoHost Container Files

~/Download
*(if needed, curl stuff here)*


Achte auf groß/kleinschreibung! Bei linux sind die Userordner (Documents, Downloads, Pictures, etc) immer groß geschrieben. Alles andere kann ja kleingeschrieben werden, aber das sollte beachtet werden.