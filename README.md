<div dir='auto'>

# من درگیر امتحانات و شلوغی کارهای این روزها شدم و فرصت نکردم این repo رو مرتب و به روز کنم. از ۱۵ مرداد سرم خلوت تر میشه و قصد دارم این ریپو رو تکمیل و مرتب کنم.
    
## این چیست؟
راه اندازی یک سیستم خانگی کامل و خوب برای یک سیستم ادمین/برنامه‌نویس/مهندس شبکه و خلاصه یک گیک کامپیوتری زمان بره! اینجا با Ansible به کارها سرعت میدیم. من در حال حاضر از لینوکس Mint 19.3 استفاده میکنم.

اقداماتی که به زودی برای عمومی تر کردن پروژه باید انجام بشه:

- **تشخیص خودکار توزیع نصب شده** (یعنی کاربر بدون دغدغه فقط نصب کنه و به تفاوت های توزیع ها کاری نداشته باشه!)
- **ساختن پنل وب برای مدیریت گرافیکی و راحت تر** (یعنی کاربر بتونه با یک پنل گرافیکی هم انسیبل رو روی سیستمش نصب کنه و هم بتونه لیست نرم افزارها و نسخه هاشون رو ببینه و با چند تا کلیک نصب کنه همه چیزو!)
- **پشتیبانی از سیستم عامل ویندوز!**
- **اضافه کردن نسخه بندی برای هر نرم افزار** (کاربر بتونه بین نسخه ها انتخاب کنه. مثلا نسخه چند داکر رو میخواد یا حتی نسخه چند ادیتورشو و ...)
</div>

## Software && Services configuration on my Homelab (by categroy)

#### general 

- [x] Update my repository
- [x] Clean unnecessary packages
- [x] Config Timezone to Asia/Tehran


#### containers and orchestration tool

- [ ] install docker
- [ ] install docker-compose
- [ ] install k8s (minikube)

#### editors and software Development tools 

- [x] install gedit
- [ ] install vscode
- [ ] install sublime
- [ ] install vim
- [ ] install postman

#### terminal emulators and shell utilities

- [x] install terminator
- [x] install konsole
- [ ] install zsh + ohmyzsh
- [ ] config default shell to zsh
- [x] Install bat


#### kernel configs

- [x] Increase max_user_watches in kernel

#### programming languages

- [ ] install latest stable php + composer
- [ ] install latest stable golang
- [ ] install latest stable python + pip
- [ ] install latest stable nodejs + npm

##### browsers

- [x] install chromium
- [x] install firefox


#### media

- [ ] install vlc
- [ ] install kazam

#### design and image editing 

- [ ] install gimp
- [ ] install inkscape
- [ ] install shotwell

#### virtualization

- [ ] install virtualbox

#### ftp/ssh/http(s)

- [x] install filezilla

#### system tools

- [ ] install ghex

#### database tools

- [ ] install sqlitebrowser
- [ ] mysqlworkbrench
- [ ] phpmyadmin
- [ ] pgadmin
- [ ] medis


#### monitoring

- [ ] gnome-system-monitor
- [x] install htop


#### security

<div dir='auto'>

لیست دائما در حال به روز شدن و اضافه شدن ابزارهای مورد نیاز خودم + ابزارهای مرسوم و عمومی میباشد. اگر شما هم ابزاری رو دوست دارید اضافه کنید کافیه پروژه رو فورک کنید و ابزارهاتونو اضافه کنید و بعد  pull request بدید. اگر هم زمان و حوصله این کار رو ندارید یا حتی کار با ansible رو بلد نیستید توی issues  بگید که افرادی که فرصت و توانایی‌شو داشته باشن انجام بدن.

</div>

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
