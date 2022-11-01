# f5-fix
fix f5 vpn to use client vpn only for client internal network resources

# How to use
- Connect to F5 VPN first
- To fix route table: `sudo ./f5 --fix`
- To restore route to default: `sudo ./f5 --restore`