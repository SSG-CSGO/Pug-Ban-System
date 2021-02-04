# Pug-Ban-System
A csgo plugin that can auto-ban players if they leave wen match is living

If you want to use this,please sure that you are already installed PUG
# Cvars:

	sm_pug_servernumber 1/2/3...  -Server number,each server shouldn't be same.
	
	sm_pug_bantime  -Bantime,minutes (default:1440)
	
	sm_pug_canleavemsg "" -Wen players can leave,print to chat。
	
# Database:

	"pug-ban"
	
{

    "driver"                        "mysql"
    
    "host"                                "DB_HOST"
    
     "database"                        "DB_NAME"
     
     "user"                                "DB_USER"
     
    "pass"                                "DB_PASS"
    
}
