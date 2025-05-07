# quick-db

Attempting to create my own SQL query builder for PHP lets see how it goess.

Initially triggered by some frustrations with existing libraries I'll be looking to addressing some personal pain points with queries that need to be created based on a series of complex logical switches with nested joins and aggregations into JSON object arrays etc.

I will investigate using MysqlI instead of PDO, its less flexible but much faster and prety much every project Ive even worked on in php my entire life has used Mysql and there the one time I did use MysqlI (many years ago) i found its ability to directly map results into class objects without deserialization quite handy.

Im not ruling PDO out entirely tho.
