### Reading Until the end of the File
- The **eof()** function returns true if the previous stream operation reached the end of the file
- The **fail()** function returns true if the previous stream operation had an error
---
### Input Stream Errors
- A **stream error** occurs when insertion or extraction fails, causing the stream to enter an error state

| Flag    | Meaning                                                                                                                           | Function                                                                                                          |
| ------- | --------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| goodbit | indicates no error flags are set and the stream is good                                                                           | **good()** returns true if no stream errors have occured                                                          |
| eofbit  | indicates if end-of-file reached on extraction                                                                                    | **eof()** returns value of eofbit, if end-of-file reached on extraction                                           |
| failbit | indicates a logical error for the previous extraction or insertion operation                                                      | **fail()** returns true if either failbit or badbit is set, indicating an error for the previous stream operation |
| badbit  | indicates an error occured while reading or writing the stream, and the stream is bad. Further operations on the stream will fail | **bad()** returns true if badbit is set, indicating the stream is bad                                             |
