## WordPress Plugin Customization

###

#### 🔗 Link https://wordpress.org/plugins/aryo-activity-log/

``
TOPIC: Remove menu from Dashboard``

```bash

add_action( 'admin_init', 'wpse_136058_remove_menu_pages' );
function wpse_136058_remove_menu_pages() {
remove_menu_page( 'activity_log_page' );
}

```