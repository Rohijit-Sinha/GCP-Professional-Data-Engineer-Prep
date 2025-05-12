### Introduction to Google Cloud Bigtable
Highly scalable NoSQL, wide column database designed for handling large volumes of data efficiently.

[<img src="images/bigtable.webp">]

Bigtable is a sparsely populated table that can scale to billions of rows and thousands of columns, enabling you to store terabytes or even petabytes of data.
A single value in each row is indexed; this value is known as the row key.
Bigtable is ideal for storing large amounts of single-keyed data with low latency. It supports high read and write throughput at low latency, and it's an ideal data source for MapReduce operations.

Bigtable is **ideal** for applications that **need high throughput and scalability** for **key-value data**, where each value is typically no larger than 10 MB. Bigtable also excels as a storage engine for batch MapReduce operations, stream processing/analytics, and machine-learning applications.

