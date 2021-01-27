_[std](../../modules/std/std-module.md):[std.memory](../../modules/std/std-memory.md).DataBuffer_
##### Class DataBuffer Extends [Resource](../../modules/std/std-resource-resource.md)
DataBuffer class.

| Constructors | |
|:---|:---|
| [New](std-memory-databuffer-new.md) | Creates a new data buffer. |

| Properties | |
|:---|:---|
| [ByteOrder](std-memory-databuffer-byteorder.md) | The byte order of the databuffer. |
| [Data](std-memory-databuffer-data.md) | A raw pointer to the databuffer's internal memory. _(read only)_ |
| [Length](std-memory-databuffer-length.md) | The length of the databuffer in bytes. _(read only)_ |

| Methods | |
|:---|:---|
| [Compress](std-memory-databuffer-compress.md) | Compresses data buffer. |
| [CopyTo](std-memory-databuffer-copyto.md) | Copies databuffer data to another databuffer. |
| [Decompress](std-memory-databuffer-decompress.md) | Decompresses data buffer. |
| [PeekByte](std-memory-databuffer-peekbyte.md) | Reads a byte from the databuffer. |
| [PeekCString](std-memory-databuffer-peekcstring.md) | Reads a null terminated CString from the databuffer. |
| [PeekDouble](std-memory-databuffer-peekdouble.md) | Reads a 64 bit double from the databuffer. |
| [PeekFloat](std-memory-databuffer-peekfloat.md) | Reads a 32 bit float from the databuffer. |
| [PeekInt](std-memory-databuffer-peekint.md) | Reads a 32 bit int from the databuffer. |
| [PeekLong](std-memory-databuffer-peeklong.md) | Reads a 64 bit long from the databuffer. |
| [PeekShort](std-memory-databuffer-peekshort.md) | Reads a 16 bit short from the databuffer. |
| [PeekString](std-memory-databuffer-peekstring.md) | Reads a string from the databuffer. |
| [PeekUByte](std-memory-databuffer-peekubyte.md) | Reads a ubyte from the databuffer. |
| [PeekUInt](std-memory-databuffer-peekuint.md) | Reads a 32 bit uint from the databuffer. |
| [PeekULong](std-memory-databuffer-peekulong.md) | Reads a 64 bit ulong from the databuffer. |
| [PeekUShort](std-memory-databuffer-peekushort.md) | Reads a 16 bit ushort from the databuffer. |
| [PokeByte](std-memory-databuffer-pokebyte.md) | Writes a byte to the databuffer. |
| [PokeCString](std-memory-databuffer-pokecstring.md) | Writes a null terminated CString to the data buffer. |
| [PokeDouble](std-memory-databuffer-pokedouble.md) | Writes a 64 bit double to the databuffer |
| [PokeFloat](std-memory-databuffer-pokefloat.md) | Writes a 32 bit float to the databuffer |
| [PokeInt](std-memory-databuffer-pokeint.md) | Writes a 32 bit int to the databuffer |
| [PokeLong](std-memory-databuffer-pokelong.md) | Writes a 64 bit long to the databuffer |
| [PokeShort](std-memory-databuffer-pokeshort.md) | Writes a 16 bit short to the databuffer |
| [PokeString](std-memory-databuffer-pokestring.md) | Write a string to the databuffer. |
| [PokeUByte](std-memory-databuffer-pokeubyte.md) | Writes an unsigned byte to the databuffer. |
| [PokeUInt](std-memory-databuffer-pokeuint.md) | Writes a 32 bit unsigned int to the databuffer |
| [PokeULong](std-memory-databuffer-pokeulong.md) | Writes a 64 bit unsigned long to the databuffer |
| [PokeUShort](std-memory-databuffer-pokeushort.md) | Writes a 16 bit unsigned short to the databuffer |
| [Resize](std-memory-databuffer-resize.md) | Resizes the databuffer. |
| [Save](std-memory-databuffer-save.md) | Saves the contents of the databuffer to a file. |
| [Slice](std-memory-databuffer-slice.md) | Creates a slice of the databuffer. |

| Functions | |
|:---|:---|
| [Load](std-memory-databuffer-load.md) | Creates a databuffer with the contents of a file. |

| Protected methods | |
|:---|:---|
| [OnDiscard](std-memory-databuffer-ondiscard.md) |  |
| [OnFinalize](std-memory-databuffer-onfinalize.md) |  |
