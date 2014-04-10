Perl script to support tab on urxvt.

###Install
To install clone the repository:

    git clone https://github.com/shaggytwodope/tabbedex-urxvt.git
    cd tabbedex-urxvt
    sudo cp tabbedex /usr/lib/urxvt/perl/tabbedex

###Configuration

    URxvt.perl-ext-common:  default,matcher,tabbedex
    URxvt.url-launcher:      dwb
    URxvt.matcher.button:   1
    URxvt.colorUL: #4682B4
    URxvt.tabbed.tabbar-fg: 2
    URxvt.tabbed.tabbar-bg: 0
    URxvt.tabbed.tab-fg: 2
    URxvt.tabbed.tab-bg: 0
    URxvt.tabbed.autohide:  yes
    URxvt.tabbed.new-button:  no
    URxvt.tabbed.title: yes
