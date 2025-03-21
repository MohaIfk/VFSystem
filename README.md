# 🔐 Secure Virtual File System with Journaling

A lightweight, secure, and crash-resilient virtual file system designed in **C++**.  
This project features journaling for data integrity, block-based AES-GCM encryption, and a modular metadata structure.

---

## ✨ Features

- ✅ **Journaling System**  
  Ensures crash recovery and atomic operations via write-ahead logging.

- 🔒 **AES-GCM Encrypted Blocks**  
  Each data block is individually encrypted with authentication for maximum security.

- 📁 **Virtual Filesystem Architecture**  
  FsNode-based design with recursive path resolution, metadata management, and permissions.

- 📓 **Efficient Block Allocation & Bitmap Management**  
  Fast tracking of used and free blocks using a scalable bitmap system.

- ♻️ **Journal Rotation & Auto Cleanup**  
  Configurable journal size with optional ring buffer or auto-prune logic.

---

## ⚙️ Technologies Used

- **C++17+**
- **AES-GCM Encryption** (via OpenSSL or other crypto libraries)
- **Custom Journaling System**
- **Modular FsNode Metadata Structure**
- *(Optional)* Boost.JSON or SQLite integration

---

## 📌 Use Cases

- 🔐 Embedded secure storage
- 🔒 Encrypted file containers
- 🎓 Academic OS/File System projects
- 🧠 High-integrity storage systems

---

## 📈 Planned Features

- CLI Tool for managing files
- Filesystem mounting layer (FUSE or custom)
- Metadata indexing and search
- Snapshot and rollback support

---

## 📄 License

MIT License

---

## 🙌 Contributions

Pull requests, suggestions, and issues are welcome!  
Let’s build a secure, modular, and educational filesystem from the ground up.

---

## 📧 Contact

For any questions, ideas, or collaboration:  
**[Mohammed ifkirne] – mohammedifkirne569@gmail.com**
