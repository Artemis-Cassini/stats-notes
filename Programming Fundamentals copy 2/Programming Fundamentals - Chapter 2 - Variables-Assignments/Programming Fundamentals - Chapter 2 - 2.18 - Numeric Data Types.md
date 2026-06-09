
| Declaration      | Size (bits) | Number range                                            |
| ---------------- | ----------- | ------------------------------------------------------- |
| char myVar;      | 8           | -128 to 127                                             |
| short myVar;     | 16          | -32,768 to 32,767                                       |
| int myVar;       | 16/32       | (32-bit) -2,147,483,648 to 2,147,483,647                |
| long myVar;      | 32/64       | (32-bit) -2,147,483,648 to 2,147,483,647                |
| long long myVar; | 64          | -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807 |
- **long long** is used for integers expected to exceed about 2 billion

| Declaration | Size    | Supported Number Range    |
| ----------- | ------- | ------------------------- |
| float x;    | 32 bits | -3.4x10x38 to 3.4x10x38   |
| double x;   | 64 bits | -1.7x10x308 to 1.7x10x308 |
- An **overflow** occurs when the value being assigned to a variable is greater than the maximum value the variable can store
