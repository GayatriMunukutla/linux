# CMPE 283 - Assignment 2: KVM Statistics

**Student():**  
- Naga Vijaya Sri Gayatri Munukutla
-018184712

**Repo:** Fork of `torvalds/linux` with changes in `arch/x86/kvm/vmx/vmx.c`
---

## 1) Team Contributions
I completed the assignment individually
---

## 2) Reproducible Steps

### A. Baseline kernel build (outer VM)
# 1) Cloned my fork
git clone https://github.com/Gayatrimunukutla/linux.git
cd linux

# 2) Configure + build
make olddefconfig 
make -j"$(nproc)"


# 3) Install + reboot
sudo make modules_install
sudo make install
sudo reboot
