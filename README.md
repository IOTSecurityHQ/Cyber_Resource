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

  - **Linux Boot Process*
      [Wiki](https://en.wikipedia.org/wiki/Booting_process_of_Linux#:~:text=In%20UEFI%20systems%2C%20the%20Linux,EFI%2Dstub%2Dbearing%20kernel.)

     

---

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

