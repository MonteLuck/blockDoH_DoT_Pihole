### Open Pi-hole Admin Interface

Access the Pi-hole web interface, typically available at [http://pi.hole/admin](http://pi.hole/admin) or `http://<your_pi-hole_ip>/admin`.

### Go to Group Management > Adlists

Navigate to **Group Management > Adlists** in the sidebar.

### Add the Blocklist

1. Click **Add a new adlist**.
2. Enter the [URL](https://raw.githubusercontent.com/MonteLuck/blockDoH_DoT_Pihole/main/list).

### Update Gravity

After adding the blocklist, go to **Tools > Update Gravity** and click **Update** to refresh Pi-hole with the new blocklist.
