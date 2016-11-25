import java.util.Scanner;

public class Leitprogramm
{
    public static void main(){
        Scanner s = new Scanner(System.in);
        System.out.println("Hallo und Herzlich Wilkommen zu diesem Programm.");
        System.out.println("Hier ist eine Auswahl von den Programmen die in dem Leitprogramm 6 vorkommen. ");
        System.out.println();
        boolean Ende1;
        Ende1 = true;
        while(Ende1 == true){
            System.out.println("Wähle ein Programm:");
            System.out.println("");
            System.out.println("Nr.1    (1)");
            System.out.println("Nr.2    (2)");
            System.out.println("Nr.3    (3)");
            System.out.println("Nr.4    (4)");
            System.out.println("Nr.5    (5)");
            System.out.println("Beenden (6) ");
            System.out.println("Gebe eine der Zahlen ein");
            int Auswahl = s.nextInt();
            int Aufgabe1Zahl = 0;
            int Aufgabe2Auswahl = 0;
            double Aufgabe2Kontostand = 512.47;
            int Aufgabe2Pin = 1234;
            int Aufgabe2Pintest = 0;
            int Aufgabe2Abheben = 0;
            int Aufgabe3Zahl = 0;
            int Aufgabe4AktTag = 0;
            int Aufgabe4AktMonat = 0;
            int Aufgabe4AktJahr = 0;
            int Aufgabe4GebTag = 0;
            int Aufgabe4GebMonat = 0;
            int Aufgabe4GebJahr = 0;
            int Aufgabe4DifTag = Aufgabe4AktTag - Aufgabe4GebTag;
            int Aufgabe4DifMonat = Aufgabe4AktMonat - Aufgabe4GebMonat;
            int Aufgabe4DifJahr = Aufgabe4AktJahr - Aufgabe4GebJahr;
            int Aufgabe4Alter = 0;
            double Aufgabe5Zahl1 = 0;
            double Aufgabe5Zahl2 = 0;
            double Aufgabe5Ergebnis = 0;
            int Aufgabe5Rechenart = 0;
            int Aufgabe6 = 0;
            if (Auswahl == 1){
                System.out.println("Wilkommen zu dem Programm zu Aufgabe 1.");
                System.out.println("Dieses Programm ist dazu dar zu testen ob eine Zahl positiv oder negativ ist.");
                while(Aufgabe1Zahl != -10){
                    System.out.println("Wenn sie wieder zur Auswahl wollen geben sie die Zahl -10 ein");
                    System.out.println("Bitte geben sie eine positive oder eine negative Zahl ein");
                    Aufgabe1Zahl = s.nextInt();
                    if(Aufgabe1Zahl < 0){
                        System.out.println("Die Eingegebene Zahl ist Negativ.");
                    }
                    else{
                        System.out.println("Die Eingegebene Zahl ist Positiv.");
                    }
                }
            }
            if (Auswahl == 2){
                System.out.println("Wilkommen zu dem Programm zu Aufgabe 2.");
                System.out.println("Dieses Programm ist dazu dar einen Bankautomaten zu Simulieren.");
                while(Aufgabe2Auswahl != -10){
                    System.out.println("Wenn sie wieder zur Auswahl wollen geben sie die Zahl -10 ein");
                    System.out.println("Bitte treffen sie erstemal wieder eine Auswahl");
                    System.out.println("Simulation starten (ohne Kontoüberziehen)    (1)");
                    System.out.println("Simulation starten (mit Kontoübereziehen)    (2)");
                    System.out.println("Simulation starten (ohne Pin ohne überziehen)(3)");
                    System.out.println("Simulation starten (ohne Pin mit überziehen) (4)");
                    System.out.println("Kontostand erfahren                          (5)");
                    System.out.println("Kontostand setzen                            (6)");
                    System.out.println("Pin erfahren                                 (7)");
                    System.out.println("Pin setzen                                   (8)");
                    Aufgabe2Auswahl = s.nextInt();
                        if(Aufgabe2Auswahl == 1){
                        while(Aufgabe2Pintest != -10){
                            System.out.println("Wilkommen bei dem Bankautomaten ihres Vertrauens.");
                            System.out.println("Bitte geben sie den Pin ein (Wenn sie -10 eingeben gehen sie zurück)");
                            Aufgabe2Pintest = s.nextInt();
                            if(Aufgabe2Pintest == Aufgabe2Pin){
                                System.out.println("Der eingegebene Pin ist richtig!");
                                System.out.println("Ihr Kontostand Beträgt " + Aufgabe2Kontostand + " Euro");
                                System.out.println("Wie viel Geld möchten sie abheben");
                                Aufgabe2Abheben = s.nextInt();
                                if(Aufgabe2Kontostand >= Aufgabe2Abheben){
                                    Aufgabe2Kontostand = Aufgabe2Kontostand - Aufgabe2Abheben;
                                    System.out.println("Es wurden Erfolgreich " + Aufgabe2Abheben + " Euro abgehoben.");
                                    System.out.println("Der neue Kontostand ist " + Aufgabe2Kontostand + "Euro");
                                
                                }
                                else{
                                    System.out.println("Da ihr Konto mit der Abbuchung überzogen wäre konnte der Gewünschte Betrag nicht abgehoben werde.");
                                    System.out.println("Wir bitten um ihr Verständnis.");
                                }
                           }
                           else{
                            System.out.println("Der eingegebene Pin ist Falsch!");
                            System.out.println("Bitte Versuchen sie es erneut.");
                           }
                        }
                    }
                    if(Aufgabe2Auswahl == 2){
                        while(Aufgabe2Pintest != -10){
                            System.out.println("Wilkommen bei dem Bankautomaten ihres Vertrauens.");
                            System.out.println("Bitte geben sie den Pin ein (Wenn sie -10 eingeben gehen sie zurück)");
                            Aufgabe2Pintest = s.nextInt();
                            if(Aufgabe2Pintest == Aufgabe2Pin){
                                System.out.println("Der eingegebene Pin ist richtig!");
                                System.out.println("Ihr Kontostand Beträgt " + Aufgabe2Kontostand + " Euro");
                                System.out.println("Wie viel Geld möchten sie abheben");
                                Aufgabe2Abheben = s.nextInt();
                                Aufgabe2Kontostand = Aufgabe2Kontostand - Aufgabe2Abheben;
                                System.out.println("Es wurden Erfolgreich " + Aufgabe2Abheben + " Euro abgehoben.");
                                System.out.println("Der neue Kontostand ist " + Aufgabe2Kontostand + "Euro");
                                
                            }
                            else{
                                System.out.println("Der eingegebene Pin ist Falsch!");
                                System.out.println("Bitte Versuchen sie es erneut.");                           
                            }
                        }
                    }
                    if(Aufgabe2Auswahl == 3){
                        while(Aufgabe2Abheben != -10){
                            System.out.println("");
                            System.out.println("Wilkommen bei dem Bankautomaten ihres Vertrauens.");
                            System.out.println("Ihr Kontostand Beträgt " + Aufgabe2Kontostand + " Euro");
                            System.out.println("Wie viel Geld möchten sie abheben(Wenn sie -10 eingeben gehen sie zurück)");
                            Aufgabe2Abheben = s.nextInt();
                            if(Aufgabe2Kontostand >= Aufgabe2Abheben){
                                Aufgabe2Kontostand = Aufgabe2Kontostand - Aufgabe2Abheben;
                                System.out.println("Es wurden Erfolgreich " + Aufgabe2Abheben + " Euro abgehoben.");
                                System.out.println("Der neue Kontostand ist " + Aufgabe2Kontostand + "Euro");              
                            }
                            else{
                                System.out.println("Da ihr Konto mit der Abbuchung überzogen wäre konnte der Gewünschte Betrag nicht abgehoben werde.");
                                System.out.println("Wir bitten um ihr Verständnis.");
                            }
                        }
                    }
                    if(Aufgabe2Auswahl == 4){
                        while(Aufgabe2Abheben != -10){
                            System.out.println("Wilkommen bei dem Bankautomaten ihres Vertrauens.");
                            System.out.println("Ihr Kontostand Beträgt " + Aufgabe2Kontostand + "  Euro");
                            System.out.println("Wie viel Geld möchten sie abheben(Wenn sie -10 eingeben gehen sie zurück)");
                            Aufgabe2Abheben = s.nextInt();
                            Aufgabe2Kontostand = Aufgabe2Kontostand - Aufgabe2Abheben;
                            System.out.println("Es wurden Erfolgreich " + Aufgabe2Abheben + " Euro abgehoben.");
                            System.out.println("Der neue Kontostand ist " + Aufgabe2Kontostand + "Euro");              
                        }
                    }
                    if(Aufgabe2Auswahl == 5){
                        System.out.println("Ihr inmomentiger Kontostand ist : " + Aufgabe2Kontostand + "Euro");
                    }
                    if(Aufgabe2Auswahl == 6){
                        System.out.println("Bitte geben sie den gewünschten Kontostand ein.");
                        Aufgabe2Kontostand = s.nextInt();
                    }
                    if(Aufgabe2Auswahl == 7){
                        System.out.println("Ihr inmomentiger in ist : " + Aufgabe2Pin);
                    }
                    if(Aufgabe2Auswahl == 8){
                        System.out.println("Bitte geben sie den gewünschten Pin ein");
                        Aufgabe2Pin = s.nextInt();
                    }
                    if (Auswahl < 0){
                        System.out.println("Falscher Wert Versuche es mit einer Zahl zwischen 1 und 8!");
                    }
                    if (Auswahl > 8){
                        System.out.println("Falscher Wert Versuche es mit einer Zahl zwischen 1 und 8!");
                    }
                }
            }
            if (Auswahl == 3){
                System.out.println("Wilkommen zu dem Programm zu Aufgabe 3.");
                System.out.println("Dieses Programm ist dazu dar zu testen ob eine Zahl positiv, negativ oder null ist.");
                while(Aufgabe3Zahl != -10){
                    System.out.println("Wenn sie wieder zur Auswahl wollen geben sie die Zahl -10 ein");
                    System.out.println("Bitte geben sie eine positive oder eine negative Zahl ein");
                    Aufgabe3Zahl = s.nextInt();
                    if(Aufgabe3Zahl < 0){
                        System.out.println("Die Eingegebene Zahl ist Negativ.");
                    }
                    if(Aufgabe3Zahl == 0){
                        System.out.println("Die Eingegebene Zahl ist null (Als ob du das nicht weißt...)");
                    }
                    if(Aufgabe3Zahl > 0){
                        System.out.println("Die Eingegebene Zahl ist Positiv.");
                    }
                }
            }
            if (Auswahl == 4){
                System.out.println("Hier soll dein Alter berechnet werden an einem Ausgewählten Zeitpunkt.");
                System.out.println("Da ich zu faul war zu testen ob es den Tag oder den Monat oder das Jahr gibt oder gab bitte ich dich es nciht auszunutzen!(so nicht --> 33.42.29235)");
                while(Aufgabe4AktTag!= -10){
                    System.out.println("Gib einen Gewünschten Tag an (eine Zahl zwischen 1-28/29/30/31)(z.b. Aktuelles Datum)");
                    Aufgabe4AktTag = s.nextInt();
                    System.out.println("Gib einen Gewünschten Monat an (eine Zahl zwischen 1-12)");
                    Aufgabe4AktMonat = s.nextInt();
                    System.out.println("Gib ein Gewünschtes Jahr ein (eine Zahlzwischen 1 und unendlich ^^ )");
                    Aufgabe4AktJahr = s.nextInt();
                    System.out.println("Gib einen Geburtstags Tag ein (eine Zahl zwischen 1-28/29/30/31)");
                    Aufgabe4GebTag = s.nextInt();
                    System.out.println("Gib einen Geburtstags Monat ein (eine Zahl zwischen 1-12)");
                    Aufgabe4GebMonat = s.nextInt();
                    System.out.println("Gib ein Geburtstags Jahr ein (eine Zahl zwischen 1 und unendlich)");
                    Aufgabe4GebJahr = s.nextInt();
                    System.out.println("Vielen Dank für die eingaben. Das Alter wird jetzt berechnet.");
                    Aufgabe4DifTag = Aufgabe4AktTag - Aufgabe4GebTag;
                    Aufgabe4DifMonat = Aufgabe4AktMonat - Aufgabe4GebMonat;
                    Aufgabe4DifJahr = Aufgabe4AktJahr - Aufgabe4GebJahr;
                    if(Aufgabe4AktMonat > Aufgabe4GebMonat){
                        Aufgabe4Alter = Aufgabe4DifJahr;
                    }
                    if(Aufgabe4AktMonat == Aufgabe4GebMonat){
                        if(Aufgabe4AktTag < Aufgabe4GebTag){
                            Aufgabe4Alter = Aufgabe4DifJahr - 1;
                        }
                        else{
                            Aufgabe4Alter = Aufgabe4DifJahr;
                        }
                    }
                    if(Aufgabe4AktMonat < Aufgabe4GebMonat){
                        Aufgabe4Alter = Aufgabe4DifJahr - 1;
                    }
                    System.out.println("");
                    System.out.println("Dein Alter beträgt " + Aufgabe4Alter);
                    if(Aufgabe4GebMonat == Aufgabe4AktMonat && Aufgabe4GebTag == Aufgabe4AktTag){
                        System.out.println("Happy Birthday!!!!!! Du hast heute Geburtstag :)  ");
                    }
                }
            }
            if (Auswahl == 5){
                System.out.println("Wilkommen bei einem Rechener (Yay)");
                while(Aufgabe5Zahl1 != -10){
                    System.out.println("Gib die erste Zahl an");
                    Aufgabe5Zahl1 = s.nextDouble();
                    System.out.println("Gib die Rechenrt an");
                    System.out.println("Addieren       (1)");
                    System.out.println("Subtrhieren    (2)");
                    System.out.println("Multiplizieren (3)");
                    System.out.println("Dividieren     (4)");
                    Aufgabe5Rechenart = s.nextInt();
                    System.out.println("Gib die zweite Zahl an");
                    Aufgabe5Zahl2 = s.nextInt();
                    if(Aufgabe5Rechenart == 1){
                        Aufgabe5Ergebnis = Aufgabe5Zahl1 + Aufgabe5Zahl2;
                    }
                    if(Aufgabe5Rechenart == 2){
                        Aufgabe5Ergebnis = Aufgabe5Zahl1 - Aufgabe5Zahl2;
                    }
                    if(Aufgabe5Rechenart == 3){
                        Aufgabe5Ergebnis = Aufgabe5Zahl1 * Aufgabe5Zahl2;
                    }
                    if(Aufgabe5Rechenart == 4){
                        Aufgabe5Ergebnis = Aufgabe5Zahl1 / Aufgabe5Zahl2;
                    }
                    if(Aufgabe5Rechenart > 4){
                        System.out.println("Versuch es mit einer Zahl zwischen 1-4");
                    }
                    if(Aufgabe5Rechenart < 1){
                        System.out.println("Versuch es mit einer Zahl zwischen 1-4");
                    }
                    System.out.println("Das Ergebnis ist : " + Aufgabe5Ergebnis);
                    
                }
            }
            if (Auswahl == 6){
                Ende1 = false;
                    
                
            }
            if (Auswahl < 0){
                System.out.println("Falscher Wert Versuche es mit einer Zahl zwischen 1 und 6!");
            }
            if (Auswahl > 6){
                System.out.println("Falscher Wert Versuche es mit einer Zahl zwischen 1 und 6!");
            }
        }
    }
}



