install( FILES
         lemon_mysql.sql
         README
         README-TAXMODELS
        DESTINATION  ${DATA_INSTALL_DIR}/lemon/ )


install( FILES
	 fix_0.9.4rc8.sql
         fix_0.9.3rc.sql
         fix_0.9.3.sql
         fix_0.9.2.sql
         fix_0.9.sql
         fix_roles.sql
	 DESTINATION  ${DATA_INSTALL_DIR}/lemon/migration )
