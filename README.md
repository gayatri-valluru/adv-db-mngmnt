Title: CoreDB: Simplified Database Management System

Project Overview:

CoreDB serves as an educational tool to delve into the intricate workings of a database management system. This initiative aims to craft a lightweight and streamlined DBMS by integrating three fundamental components pivotal to any comprehensive database system. The project is divided into three progressive assignments (PAs), each dedicated to a distinct aspect of database functionality.

PA1: Storage Manager
The initial component entails crafting a Storage Manager, serving as the cornerstone of the database system. This module oversees the physical storage of files on disk, enabling efficient reading and writing of data blocks. Key functionalities encompass initializing and overseeing a database file, ensuring data persistence through disk operations management, and facilitating the handling of data blocks within the file.

PA2: Buffer Manager
The subsequent component centers on the Buffer Manager, functioning as a cache for blocks retrieved from the disk. The Buffer Manager's primary objective is to optimize database operations by minimizing disk accesses. This module handles memory allocation for blocks, implements replacement strategies when the buffer reaches capacity, and guarantees that modified data is eventually written back to the disk to uphold data integrity.

PA3: Record Manager
The concluding component, the Record Manager, furnishes a higher level of abstraction for managing records within the database. This module empowers users to execute operations such as record navigation, insertion, and deletion. The Record Manager orchestrates the organization of records in the database, extends support for diverse data types, and ensures accurate storage and retrieval of records from blocks managed by the Buffer Manager.
