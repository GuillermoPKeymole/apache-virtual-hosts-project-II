# Apache Virtual Hosts Project – John Abbott College

This project was completed for the **Network Installation and Administration I** course at John Abbott College.

It explores advanced Apache virtual hosting techniques including:
- Name-based and port-based virtual hosts
- Subnet-based access control
- IP-based servers on different ports
- Dynamic virtual hosting using `VirtualDocumentRoot`

---

## 🔧 Project Highlights

- Root directory: `/var/www/html_project2`
- Homepage: `master_project2.html` with hyperlinks to test all tasks
- Logs and port-based access validated using firewalld and SELinux

---

## 🧱 Tasks Covered

| Task     | Description                                                        |
|----------|--------------------------------------------------------------------|
| Task 1   | Setup of project root, homepage, and base directory permissions    |
| Task 2   | Name-based and port-based virtual hosts (e.g., virtual1:80, :8000) |
| Task 3   | Subnet-restricted hosts (e.g., intranet.ici.com)                  |
| Task 4   | IP + port-based virtual servers (sales, admin, etc.)              |
| Task 5   | Dynamic virtual hosting using `VirtualDocumentRoot`               |

---

## 📂 Project Structure

- `httpd.conf` – Apache configuration
- `hosts` – Local DNS override file
- `master_project2.html` – Homepage to validate tasks
- `virtuals/` – All task-specific virtual host directories

---

## 📎 Quick Access – Key Files

🔧 **Apache Configuration**
- [`httpd.conf`](https://github.com/GuillermoPKeymole/apache-virtual-hosts-project-II/blob/main/Apache%20Virtual%20Hosts%20Project_project2/etc/httpd/conf/httpd.conf)
- [`hosts`](https://github.com/GuillermoPKeymole/apache-virtual-hosts-project-II/blob/main/Apache%20Virtual%20Hosts%20Project_project2/etc/hosts)

🖥️ **Homepage**
- [`master_project2.html`](https://github.com/GuillermoPKeymole/apache-virtual-hosts-project-II/blob/main/Apache%20Virtual%20Hosts%20Project_project2/var/www/html_project2/master_project2.html)

📁 **Virtual Host Directories**
- [`virtual1_80`](https://github.com/GuillermoPKeymole/apache-virtual-hosts-project-II/tree/main/Apache%20Virtual%20Hosts%20Project_project2/var/www/virtuals/virtual1_80)
- [`virtual1_8000`](https://github.com/GuillermoPKeymole/apache-virtual-hosts-project-II/tree/main/Apache%20Virtual%20Hosts%20Project_project2/var/www/virtuals/virtual1_8000)
- [`virtual2_80`](https://github.com/GuillermoPKeymole/apache-virtual-hosts-project-II/tree/main/Apache%20Virtual%20Hosts%20Project_project2/var/www/virtuals/virtual2_80)
- [`virtual2_8000`](https://github.com/GuillermoPKeymole/apache-virtual-hosts-project-II/tree/main/Apache%20Virtual%20Hosts%20Project_project2/var/www/virtuals/virtual2_8000)
- [`ici`](https://github.com/GuillermoPKeymole/apache-virtual-hosts-project-II/tree/main/Apache%20Virtual%20Hosts%20Project_project2/var/www/virtuals/ici)
- [`intranet`](https://github.com/GuillermoPKeymole/apache-virtual-hosts-project-II/tree/main/Apache%20Virtual%20Hosts%20Project_project2/var/www/virtuals/intranet)
- [`development`](https://github.com/GuillermoPKeymole/apache-virtual-hosts-project-II/tree/main/Apache%20Virtual%20Hosts%20Project_project2/var/www/virtuals/development)
- [`pre_production`](https://github.com/GuillermoPKeymole/apache-virtual-hosts-project-II/tree/main/Apache%20Virtual%20Hosts%20Project_project2/var/www/virtuals/pre_production)
- [`q4`](https://github.com/GuillermoPKeymole/apache-virtual-hosts-project-II/tree/main/Apache%20Virtual%20Hosts%20Project_project2/var/www/virtuals/q4)
- [`q5`](https://github.com/GuillermoPKeymole/apache-virtual-hosts-project-II/tree/main/Apache%20Virtual%20Hosts%20Project_project2/var/www/virtuals/q5)

📄 **Documents**
- [`Report PDF`](https://github.com/GuillermoPKeymole/apache-virtual-hosts-project-II/blob/main/Guillermo_PadillaKeymole_Report_P2.pdf)
- [`Instructions PDF`](https://github.com/GuillermoPKeymole/apache-virtual-hosts-project-II/blob/main/Projet-Part%20II_VHosts.pdf)
- [`Original .tar archive`](https://github.com/GuillermoPKeymole/apache-virtual-hosts-project-II/blob/main/guillermopk_project2.tar)

---

## 👨‍💻 Author

**Guillermo Padilla Keymole**  
Network Administration AEC Student  
John Abbott College
