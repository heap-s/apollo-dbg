# apollo-dbg

Apollo-dbg is the backend debugging module of the Apollo tool suite. It can run independently or within the full Apollo suite. Released under the MIT License, it welcomes all technical contributions. For documentation changes, please associate them with a corresponding patch.

---

## Overview

The primary goal of apollo-dbg (and the broader Apollo tool suite) is to serve as a go-to platform for exploit developers and reverse engineers, leveraging GDB in an extensible manner without requiring extensive user-driven functionality extensions.  
• Current Version: v0.1-alpha-rc1  
• Current Features: Basic debugging, ability to set breakpoints by function name or memory address using symbol tables, and display disassembly.

---

## For The Future

• Add a GUI frontend for the entire Apollo suite (apollo-dbg, apollo-disasm, apollo-dcmp).  
• Support more binary architectures (Windows, ARM64, etc.).  
• Improve debugging capabilities with advanced features such as enhanced register and memory visualization, heap and stack introspection, and built-in scripting for automation.

---

## Issues

Feel free to open an issue for any bugs or feature requests. We also encourage you to investigate and propose solutions. If you cannot address the issue yourself, no worries—it’ll be placed on the internal roadmap (to be made public post v0.2-beta-rc1).

---

## Maintainers

After 20 successfully merged PRs with demonstrable technical depth, you may be invited to maintain a portion of the Apollo tool suite (apollo-dbg, apollo-disasm, apollo-dcmp, or the entire suite). Upon acceptance, you agree to a 9-week development cycle culminating in new release candidates (RCs).

---

## Versioning

- Start at v0.1-alpha-rc1.  
- Each 9-week cycle aims for two RCs before incrementing the version.  
- Beta releases begin once core Apollo features are established.  
- Stable releases (e.g. v1.0-stable-rc1) emerge when Apollo is fully functional.  
- Nightly releases (e.g. v1.1-nightly-rc) address patches/bug fixes and do not merge into master.

---

*Do you see any improvements that would enhance this README?*
