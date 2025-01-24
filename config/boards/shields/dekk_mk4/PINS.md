/ {
    chosen {
        zmk,kscan = &kscan;
    };

    kscan: kscan {
        compatible = "zmk,kscan-gpio-direct";
        label = "KSCAN";***********************************************
        input-gpios = 
            <&pro_micro 1 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>, // 006
            <&pro_micro 0 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>, // 008
            <&pro_micro 2 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>, // 17
            <&pro_micro 3 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>, // 20

            <&pro_micro 4 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>, // 22
            <&pro_micro 5 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>, // 24
            <&pro_micro 6 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>, // 100
            <&pro_micro 7 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>, // 011

            <&pro_micro 8 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>, // 104
            <&pro_micro 9 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>, // 106
            <&pro_micro 21 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>, // .....

            <&pro_micro 20 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>, // 029
            <&pro_micro 19 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>, // 002
            <&pro_micro 18 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>, // 115
            <&pro_micro 15 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>, // 113

            <&pro_micro 14 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>, // 111
            <&pro_micro 16 (GPIO_ACTIVE_LOW | GPIO_PULL_UP)>; // 010
    };
};

keys to fix
* N9
* u
* s