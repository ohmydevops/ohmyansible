<div dir='auto'>
  
<center><img src="https://i.pinimg.com/originals/0f/e3/b3/0fe3b3ad1f79e320a444e037ebd3477c.jpg"></center>
  
## این چیست؟
راه اندازی یک سیستم خانگی کامل و خوب برای یک سیستم ادمین/برنامه‌نویس/مهندس شبکه و خلاصه یک گیک کامپیوتری زمان بره! اینجا با Ansible به کارها سرعت میدیم. من در حال حاضر از لینوکس Mint 19.2 استفاده میکنم.

اقداماتی که به زودی برای عمومی تر کردن پروژه باید انجام بشه:

- **تشخیص خودکار توزیع نصب شده** (یعنی کاربر بدون دغدغه فقط نصب کنه و به تفاوت های توزیع ها کاری نداشته باشه!)
- **ساختن پنل وب برای مدیریت گرافیکی و راحت تر** (یعنی کاربر بتونه با یک پنل گرافیکی هم انسیبل رو روی سیستمش نصب کنه و هم بتونه لیست نرم افزارها و نسخه هاشون رو ببینه و با چند تا کلیک نصب کنه همه چیزو!)
- **پشتیبانی از سیستم عامل ویندوز!**
- **اضافه کردن نسخه بندی برای هر نرم افزار** (کاربر بتونه بین نسخه ها انتخاب کنه. مثلا نسخه چند داکر رو میخواد یا حتی نسخه چند ادیتورشو و ...)
</div>

## Software && Services configuration on my Homelab

- [x] Update my repository
- [x] Clean unnecessary packages
- [x] Config Timezone to Asia/Tehran
- [x] Install bat
- [ ] Increase max_user_watches in kernel
- [ ] install filezilla
- [ ] install virtualbox
- [ ] install docker
- [ ] install k8s
- [ ] install gedit
- [ ] install chromium
- [ ] install firefox
- [ ] install vscode
- [ ] install sublime
- [ ] install vim
- [ ] install konsole
- [ ] install terminator
- [ ] install htop
- [ ] install zsh + ohmyzsh
- [ ] config default shell to zsh
- [ ] install ghex
- [ ] install vlc
- [ ] install sqlitebrowser
- [ ] install latest stable php + composer
- [ ] install latest stable golang
- [ ] install latest stable python + pip
- [ ] install latest stable nodejs + npm


Working on ...

## How run this with ansible?

1- **install ansbile on your system based on ansible docs**

   - apt package manager (ubuntu) :link: [link](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#latest-releases-via-apt-ubuntu)
   - apt package manager (debian) :link: [link](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#latest-releases-via-apt-debian)
   - pacman package manager (arch) :link: [link](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#latest-releases-via-pacman-arch-linux)
   - pip python package manager :link: [link](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#latest-releases-via-pip)
   - dnf/yum package manager (fedora/centos) :link: [link](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#latest-release-via-dnf-or-yum)      

2- **clone and run this repo!**


```
git clone https://github.com/amirbagh75/my-homelab-ansible.git
cd my-homelab-ansible
ansible-playbook install.yaml -K
```
