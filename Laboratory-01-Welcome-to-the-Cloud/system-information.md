# System Information

- **Linux Distribution:** Ubuntu 24.04 LTS
- **Kernel Version:** $(uname -r)
- **CPU Information:** $(lscpu | grep "Model name" | awk -F ':' '{print $2}' | xargs)
- **Total Memory:** $(free -h | awk '/Mem:/ {print $2}')
- **Available Disk Space:** $(df -h / | awk 'NR==2 {print $4}')
