# Cyber Resources

## Operating System Security Hardening

### Linux
- **Security Enhanced Linux (SELinux)**  
  [*The SELinux Notebook (4th Edition)*](https://freecomputerbooks.com/books/The_SELinux_Notebook-4th_Edition.pdf)

- **Linux Containers**  
  [YouTube Video](https://www.youtube.com/watch?v=zeMlsYJUgnY&t=1052s)

- **Linux Integrity Measurement Architecture (IMA)**  
  [Gentoo Wiki](https://wiki.gentoo.org/wiki/Integrity_Measurement_Architecture)

- **Ubuntu Hardening Guide**  
  [Blog: *What is system hardening? Definition and best practices*](https://ubuntu.com/blog/what-is-system-hardening-definition-and-best-practices)

- **Linux Kernel and Security**  
  [Linux Foundation Training](https://training.linuxfoundation.org/training/security-and-linux-kernel-lfd441/) *(this course is pricey but worth it)*

     - Linux Kernel Components
         [Background](https://developer.ibm.com/articles/l-linux-kernel/)

     - User Space vs Kernel Space
       -   [short read](https://www.linfo.org/kernel_space.html)
       -   [wiki](https://en.wikipedia.org/wiki/User_space_and_kernel_space#:~:text=Kernel%20space%20is%20strictly%20reserved,one%20address%20space%20per%20process.)
       -   [linux system calls](https://man7.org/linux/man-pages/man2/syscalls.2.html)

    - [Linux Process](https://linux-kernel-labs.github.io/refs/heads/master/lectures/processes.html)
 
    - Address Space Layout Randomization
 
      
      -   [wiki](https://en.wikipedia.org/wiki/Address_space_layout_randomization)
      -   [Linux Kernel address space layout randomization](http://selinuxproject.org/~jmorris/lss2013_slides/cook_kaslr.pdf)

  - [Kernel Self Protection](https://docs.kernel.org/security/self-protection.html)
  - [Posix Access Control](https://www.usenix.org/legacy/publications/library/proceedings/usenix03/tech/freenix03/full_papers/gruenbacher/gruenbacher_html/main.html)
  - [Control Group](https://0xax.gitbooks.io/linux-insides/content/Cgroups/linux-cgroups-1.html)
  - [SecComp](https://lwn.net/Articles/656307/)
  - [Integrity Measurement Architecture](https://ima-doc.readthedocs.io/en/latest/ima-concepts.html)
  - 



  - **Linux Boot Process**
    
    -[Wiki](https://en.wikipedia.org/wiki/Booting_process_of_Linux#:~:text=In%20UEFI%20systems%2C%20the%20Linux,EFI%2Dstub%2Dbearing%20kernel.)
    
    -[boot prcess with code](https://0xax.gitbooks.io/linux-insides/content/Booting/linux-bootstrap-1.html)

  - **Linux Kernel Module Signing**
      - [High Level](https://www.kernel.org/doc/html/v4.15/admin-guide/module-signing.html)
      - [Gentoo](https://wiki.gentoo.org/wiki/Signed_kernel_module_support)
    

 - **File System Level Encryption**
    [Kernel Doc](https://www.kernel.org/doc/html/v5.1/filesystems/fscrypt.html)

### Trusted Execution Environment

A TEE runs alongside the Rich Execution Environment (e.g., Linux) to perform security-critical functions.

- **Trusted Firmware-A**  
  [Documentation](https://trustedfirmware-a.readthedocs.io/en/latest/)

- **Android Trusted Execution Environment**  
  [Android Source Docs](https://source.android.com/docs/security/features/trusty)

- **Application Platform Security (Apple)**  
  [*Apple Platform Security Guide*](https://help.apple.com/pdf/security/en_US/apple-platform-security-guide.pdf)

---

### Email Security

- **NIST Special Publication 800-177 Revision 1**  
  [Email Security Guidelines](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-177r1.pdf)

### Low Level Security
  - **CHIPSec**
    [https://chipsec.github.io]

---

### Network Security

This is mostly dealing with firwwall which restrict network traffic based on 
the IP address. There are few vendors. The best way to learn is understand how to setup CISCO, Fortigate devices.  

-**Guidelines on Firewalls and Firewall Policy**
[Firwewall Policy](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-41r1.pdf)

The industry is moving into zero trust principle which mean all network interaction must be authenticated and authorized. 
this is nist paper on zero trust.


-**NIST Zero Trust Architecture**
[NIST zero trust](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-207.pdf)

---
### Multi Factor Authentication
FIDO is open standard for implementing multifactor authentication
[FIDO](https://fidoalliance.org/specifications/)

---
### Vulnerability Management 
All products/service services can be vulnerbility. Usually componenet in product have vulnerability which transitively lead to vulnerabilty in the product. 

Common Vulnerabilty Enumeration (CVE) is database of all open vulnerabilty. The day the vulnerability is posed is called zero day. 
[CVE](https://cve.mitre.org)

To know if the product/system is vulnerable, we need to know components with vulnerability is in the product. Software Build Of Material (SBOM) are way to keep track of it. 
[SBOM](https://www.cisa.gov/sbom)

The response to vulnerabilty might include creation of patch. NIST has framework for patch management
[NIST](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-40r4.pdf)

CVSS score determine risk factor of the vulnerabily.
[CVSS](https://en.wikipedia.org/wiki/Common_Vulnerability_Scoring_System)
