Target config: `qemu_aarch64_virt_defconfig`

http://cdn.kernel.org/pub/linux/kernel/people/will/docs/qemu/qemu-arm64-howto.html

## Как получить dtb из qemu
simonthecoder.blogspot.com/2018/12/get-qemu-virt-machine-dts.html
```
qemu-system-aarch64 -machine virt,dumpdtb=/tmp/virt.dtb
```