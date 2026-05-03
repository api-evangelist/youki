# Youki (youki)
youki is an open source container runtime written in Rust that implements the OCI runtime specification as a memory-safe alternative to runc, with rootless container support, cgroups v1 and v2, seccomp filtering, and systemd integration. Maintained as a CNCF sandbox project under the youki-dev organization, youki is adopted by container engines such as containerd, Podman, and Docker for executing OCI-compliant workloads.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/youki/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Containers, Container Runtime, OCI, Rust, CNCF, Cloud Native, Kubernetes

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-03

## APIs

### Youki Container Runtime
youki is a container runtime written in Rust that implements the OCI runtime specification, providing a memory-safe and high-performance alternative to runc. It supports rootless containers, cgroups v1 and v2, seccomp filtering, capabilities, and Linux namespaces, and integrates with container engines including containerd, Podman, Docker, and Kubernetes.

**Human URL:** [https://github.com/youki-dev/youki](https://github.com/youki-dev/youki)

#### Tags:

 - Container Runtime, OCI, Rust

#### Properties

- [Documentation](https://youki-dev.github.io/youki/)
- [GettingStarted](https://youki-dev.github.io/youki/user/basic_usage.html)
- [GitHubRepository](https://github.com/youki-dev/youki)
- [ReleaseNotes](https://github.com/youki-dev/youki/releases)
- [ChangeLog](https://github.com/youki-dev/youki/blob/main/CHANGELOG.md)
- [CLI — youki CLI](https://crates.io/crates/youki)
- [SDK — libcontainer (Rust)](https://crates.io/crates/libcontainer)
- [SDK — libcgroups (Rust)](https://crates.io/crates/libcgroups)
- [SDK — liboci-cli (Rust)](https://crates.io/crates/liboci-cli)
- [CodeExamples — WebAssembly Sample](https://github.com/youki-dev/youki/tree/main/tools/wasm-sample)
- [Tutorials — Running WebAssembly Workloads](https://youki-dev.github.io/youki/user/webassembly.html)
- [JSONSchema — OCI Runtime Config Schema](json-schema/oci-runtime-config-schema.json)
- [JSONSchema — OCI Runtime State Schema](json-schema/oci-runtime-state-schema.json)
- [JSONSchema — OCI Runtime Features Schema](json-schema/oci-runtime-features-schema.json)
- [JSONSchema — OCI Runtime Linux Config Schema](json-schema/oci-runtime-config-linux.json)
- [JSONSchema — OCI Runtime Windows Config Schema](json-schema/oci-runtime-config-windows.json)
- [JSONSchema — OCI Runtime Solaris Config Schema](json-schema/oci-runtime-config-solaris.json)
- [JSONSchema — OCI Runtime FreeBSD Config Schema](json-schema/oci-runtime-config-freebsd.json)
- [JSONSchema — OCI Runtime z/OS Config Schema](json-schema/oci-runtime-config-zos.json)
- [JSONSchema — OCI Runtime VM Config Schema](json-schema/oci-runtime-config-vm.json)
- [JSONSchema — OCI Runtime Linux Features Schema](json-schema/oci-runtime-features-linux.json)
- [JSONSchema — OCI Runtime Common Definitions](json-schema/oci-runtime-defs.json)
- [JSONSchema — OCI Runtime Linux Definitions](json-schema/oci-runtime-defs-linux.json)
- [JSONSchema — OCI Runtime Windows Definitions](json-schema/oci-runtime-defs-windows.json)
- [JSONSchema — OCI Runtime VM Definitions](json-schema/oci-runtime-defs-vm.json)
- [JSONSchema — OCI Runtime z/OS Definitions](json-schema/oci-runtime-defs-zos.json)
- [JSONSchema — OCI Runtime FreeBSD Definitions](json-schema/oci-runtime-defs-freebsd.json)
- [JSONStructure — OCI Runtime Config Structure](json-structure/oci-runtime-config-structure.json)
- [JSONStructure — OCI Runtime State Structure](json-structure/oci-runtime-state-structure.json)
- [JSONStructure — OCI Runtime Features Structure](json-structure/oci-runtime-features-structure.json)
- [JSONStructure — OCI Runtime Linux Config Structure](json-structure/oci-runtime-config-linux-structure.json)
- [JSONStructure — OCI Runtime Windows Config Structure](json-structure/oci-runtime-config-windows-structure.json)
- [JSONStructure — OCI Runtime Solaris Config Structure](json-structure/oci-runtime-config-solaris-structure.json)
- [JSONStructure — OCI Runtime FreeBSD Config Structure](json-structure/oci-runtime-config-freebsd-structure.json)
- [JSONStructure — OCI Runtime z/OS Config Structure](json-structure/oci-runtime-config-zos-structure.json)
- [JSONStructure — OCI Runtime VM Config Structure](json-structure/oci-runtime-config-vm-structure.json)
- [JSONStructure — OCI Runtime Linux Features Structure](json-structure/oci-runtime-features-linux-structure.json)
- [JSONStructure — OCI Runtime Common Definitions Structure](json-structure/oci-runtime-defs-structure.json)
- [JSONStructure — OCI Runtime Linux Definitions Structure](json-structure/oci-runtime-defs-linux-structure.json)
- [JSONStructure — OCI Runtime Windows Definitions Structure](json-structure/oci-runtime-defs-windows-structure.json)
- [JSONStructure — OCI Runtime VM Definitions Structure](json-structure/oci-runtime-defs-vm-structure.json)
- [JSONStructure — OCI Runtime z/OS Definitions Structure](json-structure/oci-runtime-defs-zos-structure.json)
- [JSONStructure — OCI Runtime FreeBSD Definitions Structure](json-structure/oci-runtime-defs-freebsd-structure.json)
- [Example — OCI Runtime Config Example](examples/oci-runtime-config-example.json)
- [Example — OCI Runtime State Example](examples/oci-runtime-state-example.json)
- [Example — OCI Runtime Features Example](examples/oci-runtime-features-example.json)
- [Example — OCI Runtime Linux Config Example](examples/oci-runtime-config-linux-example.json)
- [Example — OCI Runtime Windows Config Example](examples/oci-runtime-config-windows-example.json)
- [Example — OCI Runtime Solaris Config Example](examples/oci-runtime-config-solaris-example.json)
- [Example — OCI Runtime FreeBSD Config Example](examples/oci-runtime-config-freebsd-example.json)
- [Example — OCI Runtime z/OS Config Example](examples/oci-runtime-config-zos-example.json)
- [Example — OCI Runtime VM Config Example](examples/oci-runtime-config-vm-example.json)
- [Example — OCI Runtime Linux Features Example](examples/oci-runtime-features-linux-example.json)
- [Example — OCI Runtime Common Definitions Example](examples/oci-runtime-defs-example.json)
- [Example — OCI Runtime Linux Definitions Example](examples/oci-runtime-defs-linux-example.json)
- [Example — OCI Runtime Windows Definitions Example](examples/oci-runtime-defs-windows-example.json)
- [Example — OCI Runtime VM Definitions Example](examples/oci-runtime-defs-vm-example.json)
- [Example — OCI Runtime z/OS Definitions Example](examples/oci-runtime-defs-zos-example.json)
- [Example — OCI Runtime FreeBSD Definitions Example](examples/oci-runtime-defs-freebsd-example.json)
- [JSON-LD — OCI Runtime JSON-LD Context](json-ld/youki-oci-runtime-context.jsonld)

### OCI Spec for Rust
oci-spec-rs is a Rust implementation of the OCI Runtime, Image, and Distribution Specifications, providing the data structures and types consumed by youki and other Rust-based container tooling.

**Human URL:** [https://github.com/youki-dev/oci-spec-rs](https://github.com/youki-dev/oci-spec-rs)

#### Tags:

 - OCI, Rust, Specification

#### Properties

- [GitHubRepository](https://github.com/youki-dev/oci-spec-rs)
- [SDK — oci-spec (Rust)](https://crates.io/crates/oci-spec)
- [Documentation — oci-spec API Docs](https://docs.rs/oci-spec)
- [JSONSchema — OCI Runtime Config Schema](json-schema/oci-runtime-config-schema.json)
- [JSONSchema — OCI Runtime State Schema](json-schema/oci-runtime-state-schema.json)
- [JSONSchema — OCI Runtime Features Schema](json-schema/oci-runtime-features-schema.json)
- [JSONSchema — OCI Image Config Schema](json-schema/oci-image-config-schema.json)
- [JSONSchema — OCI Image Manifest Schema](json-schema/oci-image-manifest-schema.json)
- [JSONSchema — OCI Image Index Schema](json-schema/oci-image-index-schema.json)
- [JSONSchema — OCI Image Layout Schema](json-schema/oci-image-layout-schema.json)
- [JSONSchema — OCI Image Content Descriptor Schema](json-schema/oci-image-content-descriptor.json)
- [JSONSchema — OCI Image Common Definitions](json-schema/oci-image-defs.json)
- [JSONSchema — OCI Image Descriptor Definitions](json-schema/oci-image-defs-descriptor.json)
- [JSONStructure — OCI Runtime Config Structure](json-structure/oci-runtime-config-structure.json)
- [JSONStructure — OCI Runtime State Structure](json-structure/oci-runtime-state-structure.json)
- [JSONStructure — OCI Runtime Features Structure](json-structure/oci-runtime-features-structure.json)
- [JSONStructure — OCI Runtime Linux Config Structure](json-structure/oci-runtime-config-linux-structure.json)
- [JSONStructure — OCI Runtime Windows Config Structure](json-structure/oci-runtime-config-windows-structure.json)
- [JSONStructure — OCI Runtime Solaris Config Structure](json-structure/oci-runtime-config-solaris-structure.json)
- [JSONStructure — OCI Runtime FreeBSD Config Structure](json-structure/oci-runtime-config-freebsd-structure.json)
- [JSONStructure — OCI Runtime z/OS Config Structure](json-structure/oci-runtime-config-zos-structure.json)
- [JSONStructure — OCI Runtime VM Config Structure](json-structure/oci-runtime-config-vm-structure.json)
- [JSONStructure — OCI Runtime Linux Features Structure](json-structure/oci-runtime-features-linux-structure.json)
- [JSONStructure — OCI Runtime Common Definitions Structure](json-structure/oci-runtime-defs-structure.json)
- [JSONStructure — OCI Runtime Linux Definitions Structure](json-structure/oci-runtime-defs-linux-structure.json)
- [JSONStructure — OCI Runtime Windows Definitions Structure](json-structure/oci-runtime-defs-windows-structure.json)
- [JSONStructure — OCI Runtime VM Definitions Structure](json-structure/oci-runtime-defs-vm-structure.json)
- [JSONStructure — OCI Runtime z/OS Definitions Structure](json-structure/oci-runtime-defs-zos-structure.json)
- [JSONStructure — OCI Runtime FreeBSD Definitions Structure](json-structure/oci-runtime-defs-freebsd-structure.json)
- [JSONStructure — OCI Image Config Structure](json-structure/oci-image-config-structure.json)
- [JSONStructure — OCI Image Manifest Structure](json-structure/oci-image-manifest-structure.json)
- [JSONStructure — OCI Image Index Structure](json-structure/oci-image-index-structure.json)
- [JSONStructure — OCI Image Layout Structure](json-structure/oci-image-layout-structure.json)
- [JSONStructure — OCI Image Content Descriptor Structure](json-structure/oci-image-content-descriptor-structure.json)
- [JSONStructure — OCI Image Common Definitions Structure](json-structure/oci-image-defs-structure.json)
- [JSONStructure — OCI Image Descriptor Definitions Structure](json-structure/oci-image-defs-descriptor-structure.json)
- [Example — OCI Runtime Config Example](examples/oci-runtime-config-example.json)
- [Example — OCI Runtime State Example](examples/oci-runtime-state-example.json)
- [Example — OCI Runtime Features Example](examples/oci-runtime-features-example.json)
- [Example — OCI Runtime Linux Config Example](examples/oci-runtime-config-linux-example.json)
- [Example — OCI Runtime Windows Config Example](examples/oci-runtime-config-windows-example.json)
- [Example — OCI Runtime Solaris Config Example](examples/oci-runtime-config-solaris-example.json)
- [Example — OCI Runtime FreeBSD Config Example](examples/oci-runtime-config-freebsd-example.json)
- [Example — OCI Runtime z/OS Config Example](examples/oci-runtime-config-zos-example.json)
- [Example — OCI Runtime VM Config Example](examples/oci-runtime-config-vm-example.json)
- [Example — OCI Runtime Linux Features Example](examples/oci-runtime-features-linux-example.json)
- [Example — OCI Runtime Common Definitions Example](examples/oci-runtime-defs-example.json)
- [Example — OCI Runtime Linux Definitions Example](examples/oci-runtime-defs-linux-example.json)
- [Example — OCI Runtime Windows Definitions Example](examples/oci-runtime-defs-windows-example.json)
- [Example — OCI Runtime VM Definitions Example](examples/oci-runtime-defs-vm-example.json)
- [Example — OCI Runtime z/OS Definitions Example](examples/oci-runtime-defs-zos-example.json)
- [Example — OCI Runtime FreeBSD Definitions Example](examples/oci-runtime-defs-freebsd-example.json)
- [Example — OCI Image Config Example](examples/oci-image-config-example.json)
- [Example — OCI Image Manifest Example](examples/oci-image-manifest-example.json)
- [Example — OCI Image Index Example](examples/oci-image-index-example.json)
- [Example — OCI Image Layout Example](examples/oci-image-layout-example.json)
- [Example — OCI Image Content Descriptor Example](examples/oci-image-content-descriptor-example.json)
- [Example — OCI Image Common Definitions Example](examples/oci-image-defs-example.json)
- [Example — OCI Image Descriptor Definitions Example](examples/oci-image-defs-descriptor-example.json)
- [JSON-LD — OCI Runtime JSON-LD Context](json-ld/youki-oci-runtime-context.jsonld)
- [JSON-LD — OCI Image JSON-LD Context](json-ld/youki-oci-image-context.jsonld)

## Common Properties

- [Documentation](https://youki-dev.github.io/youki/)
- [GitHubOrganization](https://github.com/youki-dev)
- [GitHubRepository](https://github.com/youki-dev/youki)
- [ReleaseNotes](https://github.com/youki-dev/youki/releases)
- [ChangeLog](https://github.com/youki-dev/youki/blob/main/CHANGELOG.md)
- [Support](https://youki-dev.github.io/youki/community/introduction.html)
- [Vocabulary — Youki Vocabulary](vocabulary/youki-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| OCI Runtime Spec Compliance | Implements the Open Container Initiative (OCI) runtime specification, allowing youki to run any OCI-compliant container alongside or in place of runc. |
| Memory-Safe Rust Implementation | Written entirely in Rust to deliver memory safety and stronger isolation guarantees than C-based container runtimes. |
| Rootless Containers | Enables running containers without root privileges to reduce host attack surface for development and multi-tenant scenarios. |
| Cgroups v1 and v2 Support | Supports both legacy cgroups v1 and modern cgroups v2 hierarchies for resource management on Linux. |
| Seccomp Filtering | Applies seccomp BPF filters to restrict syscalls available to containers and harden the runtime surface. |
| Systemd Integration | Integrates with systemd as a cgroup manager and supports systemd-managed container processes. |
| Linux Namespaces and Capabilities | Manages mount, UTS, IPC, user, PID, network, and cgroup namespaces and supports capabilities such as CAP_BPF, CAP_PERFMON, and CAP_CHECKPOINT_RESTORE. |
| Performance | Benchmarks show youki performing roughly twice as fast as runc for container create-to-delete cycles. |
| CNCF Sandbox Project | Maintained as a Cloud Native Computing Foundation sandbox project with open governance, public roadmap, and community contributors. |

## Use Cases

| Name | Description |
|------|-------------|
| Drop-In runc Replacement | Use youki as a drop-in replacement for runc in container engines to gain memory safety and performance benefits with no workload changes. |
| Rootless Container Workflows | Run containers as a non-root user for development, CI, or multi-tenant environments where elevated privileges are not desirable. |
| Kubernetes Workloads via containerd | Use youki under containerd to execute Kubernetes pods and workloads in production clusters. |
| Podman and Docker Container Execution | Configure Podman or Docker to invoke youki as the low-level OCI runtime for image execution. |
| Container Runtime Research and Education | Explore and prototype container runtime features in a memory-safe codebase suitable for systems research, security analysis, and teaching. |

## Integrations

| Name | Description |
|------|-------------|
| containerd | containerd has passed end-to-end testing against youki, enabling its use as the OCI runtime for Kubernetes and other workloads orchestrated by containerd. |
| Podman | Podman can be configured to use youki as its OCI runtime for both rootless and rootful container execution. |
| Docker | Docker can call youki as the low-level OCI runtime in place of runc for compatible workloads via daemon.json configuration. |
| Kubernetes | Kubernetes clusters can run youki indirectly through container runtimes such as containerd or CRI-O. |
| crun | youki sits alongside crun as a modern alternative to runc, focused on memory-safe systems programming in Rust. |
| systemd | Integrates with systemd for cgroup management and lifecycle control of container processes. |
| oci-spec-rs | Built on oci-spec-rs, the Rust implementation of the OCI Runtime, Image, and Distribution specifications maintained by the same organization. |

## Solutions

| Name | Description |
|------|-------------|
| Cloud Native Container Platforms | Provides a CNCF sandbox container runtime for cloud-native platforms looking to adopt a memory-safe OCI runtime under containerd or CRI-O. |
| Secure Multi-Tenant Hosts | Pairs rootless containers, seccomp filtering, and Rust memory safety to harden multi-tenant container hosts against runtime exploits. |
| Edge and Embedded Workloads | A lightweight, high-performance runtime suitable for edge and embedded deployments where resource use and predictable performance matter. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [OCI Image Config Schema](json-schema/oci-image-config-schema.json)
- [OCI Image Content Descriptor Schema](json-schema/oci-image-content-descriptor.json)
- [OCI Image Descriptor Definitions](json-schema/oci-image-defs-descriptor.json)
- [OCI Image Common Definitions](json-schema/oci-image-defs.json)
- [OCI Image Index Schema](json-schema/oci-image-index-schema.json)
- [OCI Image Layout Schema](json-schema/oci-image-layout-schema.json)
- [OCI Image Manifest Schema](json-schema/oci-image-manifest-schema.json)
- [OCI Runtime FreeBSD Config Schema](json-schema/oci-runtime-config-freebsd.json)
- [OCI Runtime Linux Config Schema](json-schema/oci-runtime-config-linux.json)
- [OCI Runtime Config Schema](json-schema/oci-runtime-config-schema.json)
- [OCI Runtime Solaris Config Schema](json-schema/oci-runtime-config-solaris.json)
- [OCI Runtime VM Config Schema](json-schema/oci-runtime-config-vm.json)
- [OCI Runtime Windows Config Schema](json-schema/oci-runtime-config-windows.json)
- [OCI Runtime z/OS Config Schema](json-schema/oci-runtime-config-zos.json)
- [OCI Runtime FreeBSD Definitions](json-schema/oci-runtime-defs-freebsd.json)
- [OCI Runtime Linux Definitions](json-schema/oci-runtime-defs-linux.json)
- [OCI Runtime VM Definitions](json-schema/oci-runtime-defs-vm.json)
- [OCI Runtime Windows Definitions](json-schema/oci-runtime-defs-windows.json)
- [OCI Runtime z/OS Definitions](json-schema/oci-runtime-defs-zos.json)
- [OCI Runtime Common Definitions](json-schema/oci-runtime-defs.json)
- [OCI Runtime Linux Features Schema](json-schema/oci-runtime-features-linux.json)
- [OCI Runtime Features Schema](json-schema/oci-runtime-features-schema.json)
- [OCI Runtime State Schema](json-schema/oci-runtime-state-schema.json)

### JSON Structure

- [OCI Image Config Structure](json-structure/oci-image-config-structure.json)
- [OCI Image Content Descriptor Structure](json-structure/oci-image-content-descriptor-structure.json)
- [OCI Image Descriptor Definitions Structure](json-structure/oci-image-defs-descriptor-structure.json)
- [OCI Image Common Definitions Structure](json-structure/oci-image-defs-structure.json)
- [OCI Image Index Structure](json-structure/oci-image-index-structure.json)
- [OCI Image Layout Structure](json-structure/oci-image-layout-structure.json)
- [OCI Image Manifest Structure](json-structure/oci-image-manifest-structure.json)
- [OCI Runtime FreeBSD Config Structure](json-structure/oci-runtime-config-freebsd-structure.json)
- [OCI Runtime Linux Config Structure](json-structure/oci-runtime-config-linux-structure.json)
- [OCI Runtime Solaris Config Structure](json-structure/oci-runtime-config-solaris-structure.json)
- [OCI Runtime Config Structure](json-structure/oci-runtime-config-structure.json)
- [OCI Runtime VM Config Structure](json-structure/oci-runtime-config-vm-structure.json)
- [OCI Runtime Windows Config Structure](json-structure/oci-runtime-config-windows-structure.json)
- [OCI Runtime z/OS Config Structure](json-structure/oci-runtime-config-zos-structure.json)
- [OCI Runtime FreeBSD Definitions Structure](json-structure/oci-runtime-defs-freebsd-structure.json)
- [OCI Runtime Linux Definitions Structure](json-structure/oci-runtime-defs-linux-structure.json)
- [OCI Runtime Common Definitions Structure](json-structure/oci-runtime-defs-structure.json)
- [OCI Runtime VM Definitions Structure](json-structure/oci-runtime-defs-vm-structure.json)
- [OCI Runtime Windows Definitions Structure](json-structure/oci-runtime-defs-windows-structure.json)
- [OCI Runtime z/OS Definitions Structure](json-structure/oci-runtime-defs-zos-structure.json)
- [OCI Runtime Linux Features Structure](json-structure/oci-runtime-features-linux-structure.json)
- [OCI Runtime Features Structure](json-structure/oci-runtime-features-structure.json)
- [OCI Runtime State Structure](json-structure/oci-runtime-state-structure.json)

### JSON-LD

- [OCI Image JSON-LD Context](json-ld/youki-oci-image-context.jsonld)
- [OCI Runtime JSON-LD Context](json-ld/youki-oci-runtime-context.jsonld)

### Examples

- [OCI Image Config Example](examples/oci-image-config-example.json)
- [OCI Image Content Descriptor Example](examples/oci-image-content-descriptor-example.json)
- [OCI Image Descriptor Definitions Example](examples/oci-image-defs-descriptor-example.json)
- [OCI Image Common Definitions Example](examples/oci-image-defs-example.json)
- [OCI Image Index Example](examples/oci-image-index-example.json)
- [OCI Image Layout Example](examples/oci-image-layout-example.json)
- [OCI Image Manifest Example](examples/oci-image-manifest-example.json)
- [OCI Runtime Config Example](examples/oci-runtime-config-example.json)
- [OCI Runtime FreeBSD Config Example](examples/oci-runtime-config-freebsd-example.json)
- [OCI Runtime Linux Config Example](examples/oci-runtime-config-linux-example.json)
- [OCI Runtime Solaris Config Example](examples/oci-runtime-config-solaris-example.json)
- [OCI Runtime VM Config Example](examples/oci-runtime-config-vm-example.json)
- [OCI Runtime Windows Config Example](examples/oci-runtime-config-windows-example.json)
- [OCI Runtime z/OS Config Example](examples/oci-runtime-config-zos-example.json)
- [OCI Runtime Common Definitions Example](examples/oci-runtime-defs-example.json)
- [OCI Runtime FreeBSD Definitions Example](examples/oci-runtime-defs-freebsd-example.json)
- [OCI Runtime Linux Definitions Example](examples/oci-runtime-defs-linux-example.json)
- [OCI Runtime VM Definitions Example](examples/oci-runtime-defs-vm-example.json)
- [OCI Runtime Windows Definitions Example](examples/oci-runtime-defs-windows-example.json)
- [OCI Runtime z/OS Definitions Example](examples/oci-runtime-defs-zos-example.json)
- [OCI Runtime Features Example](examples/oci-runtime-features-example.json)
- [OCI Runtime Linux Features Example](examples/oci-runtime-features-linux-example.json)
- [OCI Runtime State Example](examples/oci-runtime-state-example.json)

## Vocabulary

- [Youki Vocabulary](vocabulary/youki-vocabulary.yaml) — Unified taxonomy mapping 16 resources, 17 actions, 10 workflows, and 9 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
