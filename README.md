# Memory Sizes

MemorySizes provides utility methods to determine the size of structs and different texture/graphics/rendertexture formats.

## Usage

### GetStructSizeInBytes
```csharp
int structSize = MemorySizes.GetStructSizeInBytes(typeof(MyStruct));
Debug.Log("Size of MyStruct: " + structSize);
```

### GetBitsPerPixel
```csharp
int bitsPerPixel = MemorySizes.GetBitsPerPixel(RenderTextureFormat.DXT5);
Debug.Log("Bits per pixel for DXT5 texture format: " + bitsPerPixel);
```
