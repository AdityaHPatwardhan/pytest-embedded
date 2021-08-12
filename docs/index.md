--8<-- "README.md"

## Dependency Graph

```plantuml
@startmindmap
* pytest_embedded
** pytest_embedded_serial
*** pytest_embedded_serial_esp
*** pytest_embedded_jtag
** pytest_embedded_idf (serial_esp dependency is optional)
** pytest_embedded_qemu (idf dependency is optional))
@endmindmap
```