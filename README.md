# Apache Virtual Hosts Project – John Abbott College

This project was completed for the **Network Installation and Administration I** course at John Abbott College.

It explores advanced Apache virtual hosting techniques including:
- Name-based and port-based virtual hosts
- Subnet-based access control
- IP-based servers on different ports
- Dynamic virtual hosting using `VirtualDocumentRoot`

## 🔧 Project Highlights

- Root directory: `/var/www/html_project2`
- Homepage: `master_project2.html` with hyperlinks to test all tasks
- Logs and custom ports handled through `firewalld` and SELinux

## 🧱 Tasks Covered

| Task | Description |
|------|-------------|
| Task 1 | Setup project root and homepage |
| Task 2 | Name + port-based virtual hosts (e.g., virtual1.aucegep.com:8000) |
| Task 3 | Subnet-restricted virtual hosts (e.g., intranet.ici.com) |
| Task 4 | IP + port-based servers (sales, admin, etc.) |
| Task 5 | Dynamic hosting for 5 domains via one `<VirtualHost>` block |

## 📁 Files Included

- `httpd.conf` – Apache configuration
- `hosts` – Local hostname mapping
- `master_project2.html` – Homepage with validation links
- All virtual host directories (virtual1_80, q4/sales, q5/com/itmt/www, etc.)
- `Guillermo_PadillaKeymole_Report_P2.pdf` – Full report with screenshots
- `Projet-Part II_VHosts.pdf` – Official instructions

## 👨‍💻 Author

**Guillermo Padilla Keymole**  
Network Administration AEC – John Abbott College  
