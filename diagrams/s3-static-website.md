                         +---------------------+
                         |     Developer       |
                         | Uploads Website     |
                         | (HTML, CSS, JS)     |
                         +----------+----------+
                                    |
                                    v
                         +---------------------+
                         | Amazon S3 Bucket    |
                         | Static Hosting ON   |
                         | Public Access (Read)|
                         +----------+----------+
                                    |
                                    v
                         +---------------------+
                         |      Route 53       |
                         |   (Custom Domain)   |
                         +----------+----------+
                                    |
                                    v
                         +---------------------+
                         |     End User        |
                         | Accesses Website    |
                         +---------------------+
