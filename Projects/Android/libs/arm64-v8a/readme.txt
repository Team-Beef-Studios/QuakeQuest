OpenXR loader binaries are supplied by the Gradle dependency:

org.khronos.openxr:openxr_loader_for_android

Gradle extracts the generic arm64-v8a loader from that AAR into build/generated/openxr-loader/jniLibs
before packaging. Do not copy headset-specific libopenxr_loader*.so files into this folder.
