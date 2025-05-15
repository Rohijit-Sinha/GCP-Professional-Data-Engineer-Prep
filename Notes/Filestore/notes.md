Filestore instances are fully managed file servers on Google Cloud.

Google Cloud offers three main types of data storage: block, file, and object storage.

As a type of persistent file storage, Filestore supports multiple concurrent application instances accessing the same file system simultaneously.

For Google Kubernetes Engine users, for example, Filestore provides multiple reader, multiple writer access, letting you mount your GKE PersistentVolumes as read-write by many nodes.

When compared to object storage, such as Cloud Storage FUSE, while that product does offer some file system semantics, it lacks some of the more robust characteristics of file storage provided by Filestore.

### Service tiers
Filestore offers multiple service tiers that vary in capacity, performance, and features.
- **Basic tier**: File sharing, software development, web hosting, basic AI.
- **Zonal tier**: HPC, batch compute, EDA, media rendering and transcoding, advanced AI, large data sets.
- **Regional tier**: Mission-critical workloads requiring high availability.
- **Enterprise tier**: Mission-critical workloads requiring high availability.