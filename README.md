Hibernate Configuration File 🚀

This project contains a sample hibernate.cfg.xml file configured to connect a Java application using Hibernate 4.x to a MySQL 8+ database.

It includes necessary settings such as:

- Use of com.mysql.cj.jdbc.Driver (MySQL Connector/J 8+)
- JDBC URL parameters to fix public key retrieval issues (allowPublicKeyRetrieval=true)
- Correct Hibernate dialect (MySQL5Dialect) for better compatibility
- Basic entity class mappings

This configuration is suitable for development and testing purposes.  
For production, make sure to secure your database credentials and consider environment-specific configuration management.

How to Use 🛠

1. Copy hibernate.cfg.xml into your Java project’s resource folder.
2. Adjust database username, password, and other settings as needed.
3. Add Hibernate and MySQL Connector/J dependencies to your project.
4. Run your Hibernate-based application.

Author 👨‍💻

Created by Heshan Nawarathna
