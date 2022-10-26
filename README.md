# vucutkitle

import java.util.Scanner;

        double boy, kilo;
        Scanner inp = new Scanner(System.in);

        System.out.print("Lütfen boyunuzu (metre cinsinde) giriniz: ");
        boy = inp.nextDouble();
        System.out.print("Lütfen kilonuzu giriniz: ");
        kilo = inp.nextDouble();

        double formul = kilo / (boy * boy);
        System.out.print("Vücut Kitle İndeksiniz : " + formul);
