# Maintainer: Philip Müller <philm[at]manjaro[dot]org>
# Maintainer: Bernhard Landauer <bernhard[at]manjaro[dot]org>
# Maintainer: Helmut Stult <helmut[at]manjaro[dot]org>

# Arch credits:
# Contributor: Christian Hesse <mail@eworm.de>
# Contributor: Dave Reisner <dreisner@archlinux.org>
# Contributor: Tom Gundersen <teg@jklm.no>

pkgbase=systemd
pkgname=('systemd' 'systemd-libs' 'systemd-resolvconf' 'systemd-sysvcompat')
_tag='5a7886c4fde182d10aaa5e1c4e35f7fac8633ef2' # git rev-parse v${pkgver}
pkgver=246.4
pkgrel=1
arch=('x86_64')
url='https://www.github.com/systemd/systemd'
makedepends=('acl' 'cryptsetup' 'docbook-xsl' 'gperf' 'lz4' 'xz' 'pam' 'libelf'
             'intltool' 'iptables' 'kmod' 'libcap' 'libidn2' 'libgcrypt'
             'libmicrohttpd' 'libxcrypt' 'libxslt' 'util-linux' 'linux-api-headers'
             'python-lxml' 'quota-tools' 'shadow' 'gnu-efi-libs' 'git'
             'meson' 'libseccomp' 'pcre2' 'audit' 'kexec-tools' 'libxkbcommon'
             'bash-completion' 'p11-kit' 'systemd' 'zstd')
options=('strip')
validpgpkeys=('63CDA1E5D3FC22B998D20DD6327F26951A015CC4'  # Lennart Poettering <lennart@poettering.net>
              '5C251B5FC54EB2F80F407AAAC54CA336CFEB557E') # Zbigniew Jędrzejewski-Szmek <zbyszek@in.waw.pl>
source=("git+https://github.com/systemd/systemd-stable#tag=${_tag}?signed"
        "git+https://github.com/systemd/systemd#tag=v${pkgver%.*}?signed"
        '0001-Use-Manjaro-Linux-device-access-groups.patch'
        '0001-fix-systemd-issue-15699.patch'
        'initcpio-hook-udev'
        'initcpio-install-systemd'
        'initcpio-install-udev'
        'manjaro.conf'
        'loader.conf'
        'splash-manjaro.bmp'
        'systemd-user.pam'
        'systemd-hook'
        '20-systemd-sysusers.hook'
        '30-systemd-binfmt.hook'
        '30-systemd-catalog.hook'
        '30-systemd-daemon-reload.hook'
        '30-systemd-hwdb.hook'
        '30-systemd-sysctl.hook'
        '30-systemd-tmpfiles.hook'
        '30-systemd-udev-reload.hook'
        '30-systemd-update.hook')
sha512sums=('SKIP'
            'SKIP'
            'e38c7c422c82953f9c2476a5ab8009d614cbec839e4088bff5db7698ddc84e3d8ed64f32ed323f57b1913c5c9703546f794996cb415ed7cdda930b627962a3c4'
            '3dd6be816f37ad5b53f9c92fd174563b096d348ff491b11d649c913241bd3c6d8acd40a84819235a190c419fb78981f803fdd598481e20f4a820db6cf0534ebe'
            '1f800fe10d1d1c8b1ff45ae352f84dd1918f5559fbf80338b17d490a581ae5e4895c0b51baee7dac9260f4b6f9965da2fa5d33f2a5e31b1afa6c1aafce3e1e49'
            '80ac350fb4dc58c52d4c1ce77a1f91b8cd64d4c99a1c1e24194acac56f9e4a69b2304b13113e93d38459041fa073fe97840776d99ed7e4ce99aa76a3adb39583'
            'a25b28af2e8c516c3a2eec4e64b8c7f70c21f974af4a955a4a9d45fd3e3ff0d2a98b4419fe425d47152d5acae77d64e69d8d014a7209524b75a81b0edb10bf3a'
            '72dfd0e513e61f391d2b0bf8d9f13c6e2d2732dd7bd52413dccc791c562ab6265062c17d5abe60a42db0775e0b2352eba5e18d14fa2740c176d82edac4867c32'
            '363052706e8fdb040754d0bdc75377212865314ffb8718f8889e6c8a0049ea6cc442cb34fb9a204622eca597b78a547421867cb7517bd1b7342badee581bde7d'
            '6200f2844bdcd230ef4efd27313a92b663a199fe7b3cf1794d17ca4d62bb2d7e9856e6a6e2ea0b912955df124c9d97374c70ae4ef2ff092b25296769fe9e8ba7'
            'b90c99d768dc2a4f020ba854edf45ccf1b86a09d2f66e475de21fe589ff7e32c33ef4aa0876d7f1864491488fd7edb2682fc0d68e83a6d4890a0778dc2d6fe19'
            '869dab2b1837c964add4019bb402e24e52dbb7f009850ca69fcc5deddd923eeb98eb8ee38601f6e31531f30322472fe7df09af84df27f0467708406c55885323'
            '299dcc7094ce53474521356647bdd2fb069731c08d14a872a425412fcd72da840727a23664b12d95465bf313e8e8297da31259508d1c62cc2dcea596160e21c5'
            '0d6bc3d928cfafe4e4e0bc04dbb95c5d2b078573e4f9e0576e7f53a8fab08a7077202f575d74a3960248c4904b5f7f0661bf17dbe163c524ab51dd30e3cb80f7'
            '2b50b25e8680878f7974fa9d519df7e141ca11c4bfe84a92a5d01bb193f034b1726ea05b3c0030bad1fbda8dbb78bf1dc7b73859053581b55ba813c39b27d9dc'
            '63e55b3acd14bc54320b6f2310b43398651ad4e262d4f4a0135e05d34a993e56ed673cc46e57f15b418371df5c4cef6f54486db96325e4abb1d33fb1a3946254'
            'a1661ab946c6cd7d3c6251a2a9fd68afe231db58ce33c92c42594aedb5629be8f299ba08a34713327b373a3badd1554a150343d8d3e5dfb102999c281bd49154'
            '9426829605bbb9e65002437e02ed54e35c20fdf94706770a3dc1049da634147906d6b98bf7f5e7516c84068396a12c6feaf72f92b51bdf19715e0f64620319de'
            'da7a97d5d3701c70dd5388b0440da39006ee4991ce174777931fea2aa8c90846a622b2b911f02ae4d5fffb92680d9a7e211c308f0f99c04896278e2ee0d9a4dc'
            'a50d202a9c2e91a4450b45c227b295e1840cc99a5e545715d69c8af789ea3dd95a03a30f050d52855cabdc9183d4688c1b534eaa755ebe93616f9d192a855ee3'
            '825b9dd0167c072ba62cabe0677e7cd20f2b4b850328022540f122689d8b25315005fa98ce867cf6e7460b2b26df16b88bb3b5c9ebf721746dce4e2271af7b97')

_backports=(
)

_reverts=(
)

prepare() {
  cd "$pkgbase-stable"

  # add upstream repository for cherry-picking
  git remote add -f upstream ../systemd

  local _c
  for _c in "${_backports[@]}"; do
    git log --oneline -1 "${_c}"
    git cherry-pick -n "${_c}"
  done
  for _c in "${_reverts[@]}"; do
    git log --oneline -1 "${_c}"
    git revert -n "${_c}"
  done

  # Replace cdrom/dialout/tape groups with optical/uucp/storage
  patch -Np1 -i ../0001-Use-Manjaro-Linux-device-access-groups.patch

  # https://github.com/systemd/systemd/issues/15699
  # https://github.com/systemd/systemd/issues/16076
  patch -Np1 -i ../0001-fix-systemd-issue-15699.patch
}

build() {
  local _timeservers=({0..3}.manjaro.pool.ntp.org)
  local _nameservers=(
    # We use these public name services, ordered by their
    # privacy policy (hopefully):
    #  * Cloudflare (https://1.1.1.1/)
    #  * Quad9 without filtering (https://www.quad9.net/)
    #  * Google (https://developers.google.com/speed/public-dns/)
    1.1.1.1
    9.9.9.10
    8.8.8.8
    2606:4700:4700::1111
    2620:fe::10
    2001:4860:4860::8888
  )

  local _meson_options=(
    -Dversion-tag="${pkgver}-${pkgrel}-manjaro"

    -Dgnu-efi=true
    -Dima=false
    -Dlibidn2=true
    -Dlz4=true
    -Dman=true

    -Ddbuspolicydir=/usr/share/dbus-1/system.d
    -Ddefault-hierarchy=hybrid
    -Ddefault-kill-user-processes=false
    -Ddefault-locale=C
    -Ddns-over-tls=openssl
    -Dfallback-hostname='manjaro'
    -Dnologin-path=/usr/bin/nologin
    -Dntp-servers="${_timeservers[*]}"
    -Ddns-servers="${_nameservers[*]}"
    -Drpmmacrosdir=no
    -Dsysvinit-path=
    -Dsysvrcnd-path=
    -Dapparmor=false
    -Dsupport-url='https://forum.manjaro.org/c/support'
  )

  arch-meson "$pkgbase-stable" build "${_meson_options[@]}"

  ninja -C build
}

check() {
  meson test -C build
}

package_systemd() {
  pkgdesc='system and service manager'
  license=('GPL2' 'LGPL2.1')
  depends=('acl' 'libacl.so' 'bash' 'cryptsetup' 'libcryptsetup.so' 'dbus'
           'iptables' 'kbd' 'kmod' 'libkmod.so' 'hwids' 'libcap' 'libcap.so'
           'libgcrypt' 'libxcrypt' 'libcrypt.so' 'systemd-libs' 'libidn2' 'libidn2.so' 'lz4' 'pam'
           'libelf' 'libseccomp' 'libseccomp.so' 'util-linux' 'libblkid.so'
           'libmount.so' 'xz' 'pcre2' 'audit' 'libaudit.so' 'libp11-kit'
           'libp11-kit.so' 'openssl')
  provides=('nss-myhostname' "systemd-tools=$pkgver" "udev=$pkgver")
  replaces=('nss-myhostname' 'systemd-tools' 'udev')
  conflicts=('nss-myhostname' 'systemd-tools' 'udev')
  optdepends=('libmicrohttpd: remote journald capabilities'
              'quota-tools: kernel-level quota management'
              'systemd-sysvcompat: symlink package to provide sysvinit binaries'
              'polkit: allow administration as unprivileged user'
              'curl: machinectl pull-tar and pull-raw')
  backup=(etc/pam.d/systemd-user
          etc/systemd/coredump.conf
          etc/systemd/journald.conf
          etc/systemd/journal-remote.conf
          etc/systemd/journal-upload.conf
          etc/systemd/logind.conf
          etc/systemd/networkd.conf
          etc/systemd/resolved.conf
          etc/systemd/sleep.conf
          etc/systemd/system.conf
          etc/systemd/timesyncd.conf
          etc/systemd/user.conf
          etc/udev/udev.conf)
  install=systemd.install

  DESTDIR="$pkgdir" meson install -C build

  # we'll create this on installation
  rmdir "$pkgdir"/var/log/journal/remote

  # runtime libraries shipped with systemd-libs
  install -d -m0755 systemd-libs
  mv "$pkgdir"/usr/lib/lib{nss,systemd,udev}*.so* systemd-libs

  # manpages shipped with systemd-sysvcompat
  rm "$pkgdir"/usr/share/man/man8/{halt,poweroff,reboot,shutdown}.8

  # executable (symlinks) shipped with systemd-sysvcompat
  rm "$pkgdir"/usr/bin/{halt,init,poweroff,reboot,shutdown}

  # files shipped with systemd-resolvconf
  rm "$pkgdir"/usr/{bin/resolvconf,share/man/man1/resolvconf.1}

  # avoid a potential conflict with [core]/filesystem
  rm "$pkgdir"/usr/share/factory/etc/{issue,nsswitch.conf}
  sed -i -e '/^C \/etc\/nsswitch\.conf/d' \
    -e '/^C \/etc\/issue/d' "$pkgdir"/usr/lib/tmpfiles.d/etc.conf

  # add back tmpfiles.d/legacy.conf, normally omitted without sysv-compat
  install -m0644 $pkgbase-stable/tmpfiles.d/legacy.conf "$pkgdir"/usr/lib/tmpfiles.d

  # ship default policy to leave services disabled
  echo 'disable *' >"$pkgdir"/usr/lib/systemd/system-preset/99-default.preset

  # add mkinitcpio hooks
  install -D -m0644 initcpio-install-systemd "$pkgdir"/usr/lib/initcpio/install/systemd
  install -D -m0644 initcpio-install-udev "$pkgdir"/usr/lib/initcpio/install/udev
  install -D -m0644 initcpio-hook-udev "$pkgdir"/usr/lib/initcpio/hooks/udev

  # The group 'systemd-journal' is allocated dynamically and may have varying
  # gid on different systems. Let's install with gid 0 (root), systemd-tmpfiles
  # will fix the permissions for us. (see /usr/lib/tmpfiles.d/systemd.conf)
  install -d -o root -g root -m 2755 "$pkgdir"/var/log/journal

  # match directory owner/group and mode from [extra]/polkit
  install -d -o root -g 102 -m 0750 "$pkgdir"/usr/share/polkit-1/rules.d

  # add example bootctl configuration
  install -D -m0644 manjaro.conf "$pkgdir"/usr/share/systemd/bootctl/manjaro.conf
  install -D -m0644 loader.conf "$pkgdir"/usr/share/systemd/bootctl/loader.conf
  install -D -m0644 splash-manjaro.bmp "$pkgdir"/usr/share/systemd/bootctl/splash-manjaro.bmp

  # pacman hooks
  install -D -m0755 systemd-hook "$pkgdir"/usr/share/libalpm/scripts/systemd-hook
  install -D -m0644 -t "$pkgdir"/usr/share/libalpm/hooks *.hook

  # overwrite the systemd-user PAM configuration with our own
  install -D -m0644 systemd-user.pam "$pkgdir"/etc/pam.d/systemd-user
}

package_systemd-libs() {
  pkgdesc='systemd client libraries'
  depends=('glibc' 'libcap' 'libgcrypt' 'lz4' 'xz' 'zstd')
  license=('LGPL2.1')
  provides=('libsystemd' 'libsystemd.so' 'libudev.so')
  conflicts=('libsystemd')
  replaces=('libsystemd')

  install -d -m0755 "$pkgdir"/usr
  mv systemd-libs "$pkgdir"/usr/lib
}

package_systemd-resolvconf() {
  pkgdesc='systemd resolvconf replacement (for use with systemd-resolved)'
  license=('LGPL2.1')
  depends=('systemd')
  provides=('openresolv' 'resolvconf')
  conflicts=('openresolv')

  install -d -m0755 "$pkgdir"/usr/bin
  ln -s resolvectl "$pkgdir"/usr/bin/resolvconf

  install -d -m0755 "$pkgdir"/usr/share/man/man1
  ln -s resolvectl.1.gz "$pkgdir"/usr/share/man/man1/resolvconf.1.gz
}

package_systemd-sysvcompat() {
  pkgdesc='sysvinit compat for systemd'
  license=('GPL2')
  conflicts=('sysvinit')
  depends=('systemd')

  install -D -m0644 -t "$pkgdir"/usr/share/man/man8 \
    build/man/{halt,poweroff,reboot,shutdown}.8

  install -d -m0755 "$pkgdir"/usr/bin
  ln -s ../lib/systemd/systemd "$pkgdir"/usr/bin/init
  for tool in halt poweroff reboot shutdown; do
    ln -s systemctl "$pkgdir"/usr/bin/$tool
  done
}

# vim:ft=sh syn=sh et sw=2:
