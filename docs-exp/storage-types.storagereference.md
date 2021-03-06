<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/storage-types](./storage-types.md) &gt; [StorageReference](./storage-types.storagereference.md)

## StorageReference interface

Represents a reference to a Google Cloud Storage object. Developers can upload, download, and delete objects, as well as get/set object metadata.

<b>Signature:</b>

```typescript
export interface StorageReference 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [bucket](./storage-types.storagereference.bucket.md) | string | The name of the bucket containing this reference's object. |
|  [fullPath](./storage-types.storagereference.fullpath.md) | string | The full path of this object. |
|  [name](./storage-types.storagereference.name.md) | string | The short name of this object, which is the last component of the full path. For example, if fullPath is 'full/path/image.png', name is 'image.png'. |
|  [parent](./storage-types.storagereference.parent.md) | [StorageReference](./storage-types.storagereference.md) \| null | A reference pointing to the parent location of this reference, or null if this reference is the root. |
|  [root](./storage-types.storagereference.root.md) | [StorageReference](./storage-types.storagereference.md) | A reference to the root of this object's bucket. |
|  [storage](./storage-types.storagereference.storage.md) | [StorageService](./storage-types.storageservice.md) | The StorageService associated with this reference. |

## Methods

|  Method | Description |
|  --- | --- |
|  [toString()](./storage-types.storagereference.tostring.md) | Returns a gs:// URL for this object in the form <code>gs://&lt;bucket&gt;/&lt;path&gt;/&lt;to&gt;/&lt;object&gt;</code> |

