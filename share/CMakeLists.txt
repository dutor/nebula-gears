install(
    FILES
        nebula-gears/gcc-tarball-info-5.1.0
        nebula-gears/gcc-tarball-info-5.3.0
        nebula-gears/gcc-tarball-info-5.5.0
        nebula-gears/gcc-tarball-info-6.1.0
        nebula-gears/gcc-tarball-info-6.3.0
        nebula-gears/gcc-tarball-info-6.5.0
        nebula-gears/gcc-tarball-info-7.1.0
        nebula-gears/gcc-tarball-info-7.3.0
        nebula-gears/gcc-tarball-info-7.5.0
        nebula-gears/gcc-tarball-info-8.3.0
        nebula-gears/gcc-tarball-info-9.1.0
        nebula-gears/gcc-tarball-info-9.2.0
        nebula-gears/gcc-tarball-info-9.3.0
        nebula-gears/gcc-tarball-info-10.1.0
        nebula-gears/llvm-tarball-info-8.0.0
        nebula-gears/llvm-tarball-info-9.0.0
        nebula-gears/llvm-tarball-info-10.0.0
        nebula-gears/gdb-tarball-info-8.3
    PERMISSIONS
        OWNER_READ OWNER_WRITE
        GROUP_READ
        WORLD_READ
    DESTINATION
        share/nebula-gears
)
