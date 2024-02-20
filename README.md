# PraktikumSatria_anugra_1

[Package.docx](https://github.com/SatriaAnugra/PraktikumSatria_anugra_1/files/14339988/Package.docx)

import java.time.LocalTime;
import java.time.ZoneId;

public class JakartaLocalTimeExample {

    public static void main(String[] args) {
        // Specify the time zone for Jakarta
        ZoneId jakartaZone = ZoneId.of("Asia/Jakarta");

        // Get the current time in Jakarta time zone
        LocalTime currentTimeInJakarta = LocalTime.now(jakartaZone);

        // Display the current time in Jakarta
        System.out.println("Current time in Jakarta: " + currentTimeInJakarta);
    }
}


import java.time.LocalDateTime;
import java.time.ZoneId;

public class JakartaLocalDateTimeExample {

    public static void main(String[] args) {
        // Specify the time zone for Jakarta
        ZoneId jakartaZone = ZoneId.of("Asia/Jakarta");

        // Get the current date and time in Jakarta time zone
        LocalDateTime currentDateTimeInJakarta = LocalDateTime.now(jakartaZone);

        // Display the current date and time in Jakarta
        System.out.println("Current date and time in Jakarta: " + currentDateTimeInJakarta);
    }
}
