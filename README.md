# The-Errors--Alternate-State-of-Mindimport java.util.Scanner;
public class Main
{
public static void main(String[] args)
   {
    Scanner console = new Scanner(System.in);
    System.out.println("Welcome to an Altered State of mind!");
    System.out.println("Please enter a number from 1-7 to get draw a random drug.");
    int x= console.nextInt();
    console.nextLine();
    String drug= "";
    switch (x)
     {
        case 1:
             drug="Alcohol";
           break;
        case 2:
             drug="LSD";
            break;
        case 3:
            drug="Meth";
            break;
        case 4:
             drug="Cocaine";
           break;
        case 5:
             drug="Heroin";
            break;
        case 6:
            drug="Marijuana";
            break;
        case 7:
            drug="Nicotine";
            break;
        default:
             System.out.println("Please enter a number from 1-7.");
      }
    switch (x)
     {
         case 1:
          System.out.print("The drug you got is Alcohol. The four types of alcohol are ethyl, denatured,"); 
          System.out.print(" isopropyl and rubbing.The one that we know and love the best is ethyl alcohol, also called ethanol");
          System.out.print(" or grain alcohol. It's made by fermenting sugar and yeast, and is used in beer, wine, and liquor.");
          System.out.println();
           break;
        case 2:
            System.out.print("The drug you got is LSD. A synthetic crystalline compound, lysergic acid diethylamide, that is a potent hallucinogenic drug.");
            System.out.println();
            break;
        case 3:
            System.out.print("The drug you got is Meth. Methamphetamine is a powerful, highly addictive stimulant that");
            System.out.print(" affects the central nervous system. It takes the form of a white, odorless, bitter-tasting");
            System.out.print(" crystalline powder that easily dissolves in water or alcohol."); 
            System.out.println();
            break;
        case 4:
            System.out.print("The drug you got is Cocaine. Cocaine is a powerfully addictive stimulant drug. For thousands of years, people in");
            System.out.print(" South America have chewed and ingested coca leaves");
            System.out.println();
            break;
        case 5:
            System.out.println("The drug you got is Heroin. A highly addictive analgesic drug derived from morphine, often used illicitly as a narcotic producing euphoria."); 
           break;
        case 6:
            System.out.println("The drug you got is Marijuana. Marijuana, which can also be called weed, pot, dope, or cannabis, is the dried flowers and leaves of the cannabis plant. It contains mind-altering compounds, as well as other active compounds that are not mind-altering.");  
            break;
        case 7:
            System.out.println("The drug you got is Nicotine. A toxic colorless or yellowish oily liquid that is the chief active constituent of tobacco. It acts as a stimulant in small doses, but in larger amounts blocks the action of autonomic nerve and skeletal muscle cells.");
            break;
        default:
            System.out.println("Please enter a number from 1-7.");
         
     }
     System.out.println();
    System.out.println("You are out partying with some friends and decide to partake in "+ drug+ ". Do you decide to drive your car home or call a Duber? Type 'drive' or 'duber'");
    String duber = console.nextLine();
    switch (x)
    {
        case 1:
          if(duber.equals("drive"))
          {
              System.out.println("You are drive while intoxicated and drive very recklessly, making you get noticed by a cop who makes you take a breathlyzer test. Because your are blood alcohol test was 0.8% you get your license suspended and are facing a DUI. Game Over");
          }
          else 
          {
             System.out.println("Once you have called the Duber, you decide to go around for a walk to get some fresh air before you head back home. You are not able to walk properly due to the copious amounts of alcohol you drank and you stumble and fall asleep on the side of the road. Thankfully, one of your neighbors found you and left you outside of your apartment."); 
            }
           break;
        case 2:
            if(duber.equals("drive"))
          {
              System.out.println("You drive recklessly and crash into a pole, dying on site. Game over"); 
          }
          else 
          {
             System.out.println("Once you get inside the Duber, your head starts aching and you feel like you’re trapped in a drowning car. You punch the window to try to escape and end up with a bloody arm."); 
            }
            break;
        case 3:
            if(duber.equals("drive"))
          {
              System.out.println("You drive recklessly and crash into a pole, dying on site. Game over");
          }
          else 
          {
             System.out.println("Once you get inside the Duber, you start to experience psychosis, a mental disorder in which you lose contact with reality. You start experiencing delusions that you are surfing so you climb on top of the car to “feel the waves.” The Duber driver immediately stops the car and kicks you out of the car, leaving you stranded."); 
            }
            break;
        case 4:
             if(duber.equals("drive"))
          {
              System.out.println("You drive recklessly and crash into a pole, dying on site. Game over");
          }
          else 
          {
             System.out.println("Once you get inside the Duber, you immediately start yelling at the Duber driver and begin experiencing intense mood swings. You punch the back of the Duber driver's head and are forced to leave the car."); 
            }
            break;
        case 5:
            if(duber.equals("drive"))
          {
              System.out.println("You drive recklessly and crash into a pole, dying on site. Game over");
          }
          else 
          {
             System.out.println("Once you get inside the Duber, you experience a feeling known as going on-the-nod, where you go between conscious and semi-conscious, due to the rocking of the car. You then throw up on the Duber driver and are forced to pay a cleaning fee for the car and the clothes."); 
            }
           break;
        case 6:
           if(duber.equals("drive"))
          {
              System.out.println("You drive recklessly and crash into a pole, dying on site. Game over");
          }
          else 
          {
             System.out.println("Once you get inside the Duber, all your senses become heightened. Your ears start ringing and the outside lights become blindingly bright. The loss of motor skills cause you to fall while walking back home and you are taken to the hospital by a passerby."); 
            }
            break;
        case 7:
            if(duber.equals("drive"))
          {
              System.out.println("You drive recklessly and crash into a pole, dying on site. Game over");
          }
          else 
          {
             System.out.println(" Once you get inside the Duber, your stomach starts cramping and you puke on the Duber driver. The car swerves and falls into a ditch."); 
            }
            break;
        default:
            System.out.println("Please enter a number from 1-7.");
    }
    System.out.println();
    if(duber.equals("duber"))
     {
    System.out.println("You are under the influence of "+drug+ " and you go to your workplace. Do you choose to take a vitamin drink before you go? Type 'yes' or 'no'.");
    String vitamin = console.nextLine();
    switch (x)
    {
        case 1:
          if(vitamin.equals("no"))
          {
              System.out.println("Because you didn't take care of your health and were under the influence you passed away. Game over");
          }
          else 
          {
             System.out.println("You have an extreme hangover and are not able to focus on your important development meeting. You then throw up on your desk and are asked to take a leave from work and have to take a drug test. You may be facing suspension from work."); 
            }
           break;
        case 2:
            if(vitamin.equals("no") )
          {
              System.out.println("Because you didn't take care of your health and were under the influence you passed away. Game over");
          }
          else 
          {
             System.out.println("You enter the workplace late because LSD affects the sense of time. When you are at the workplace, you are not able to type on your computer due to uncoordinated movements. Due to this, you start to have panic attacks and are taken to the hospital by worried coworkers. Because traces of LSD are found in your system, you are facing consequences both legally and from your company."); 
            }
            break;
        case 3:
            if(vitamin.equals("no"))
          {
              System.out.println("Because you didn't take care of your health and were under the influence you passed away. Game over");
          }
          else 
          {
             System.out.println("You spend the entire day working without taking time for a lunch break or dinner. Meth causes a loss of appetite, which leads you to faint in the middle of an important business meeting. You get taken to the hospital by a coworker and they find traces of meth in your system. "); 
            }
            break;
        case 4:
             if(vitamin.equals("no"))
          {
              System.out.println("Because you didn't take care of your health and were under the influence you passed away. Game over");
          }
          else 
          {
             System.out.println("You enter the workplace very irritable and easily annoyed. You yell at a few coworkers for easily fixed mistakes and have a temper tantrum in the middle of your workplace. Your manager asks to have an emergency meeting with you and warns you that if you continue such behavior, then your status at the company will be reviewed and you might be removed. "); 
            }
            break;
        case 5:
            if(vitamin.equals("no"))
          {
              System.out.println("Because you didn't take care of your health and were under the influence you passed away. Game over");
              
          }
          else 
          {
             System.out.println("While at work, the heroin in your system causes your body to slow your breathing. It gets difficult to focus on your work and your coworkers notice your abnormal behavior. They let your supervisor know and you get sent home and lose your chance to get extra vacation days. "); 
            }
           break;
        case 6:
           if(vitamin.equals("no"))
          {
              System.out.println("Because you didn't take care of your health and were under the influence you passed away. Game over");
          }
          else 
          {
             System.out.println("Because marijuana affects your interest in activities that once held importance to you, you start to not take an interest in your work and slack off. Your coworkers notice this and try to helpfully remind you that your deadline is today. At the end of the workday, you are reprimanded by your boss and are not given extra vacation days."); 
            }
            break;
        case 7:
            if(vitamin.equals("no"))
          {
              System.out.println("Because you didn't take care of your health and were under the influence you passed away. Game over");
          }
          else 
          {
             System.out.println("Throughout the day, you are prone to coughing fits and have periods of shortness of breath. You are not able to focus on your work due to this. Your coworkers notice and tell you to be more healthy in order to avoid  future health complications."); 
            }
            break;
        default:
            System.out.println("Please enter a number from 1-7.");
    
        }
        System.out.println();
        if (vitamin.equals("yes") && duber.equals("duber"))
        {
    System.out.println("Because you had a bad day at work you choose to consume "+drug+ " and go to a party. Find out how your future lays out with continued use of "+drug);
    switch (x)
        {
        case 1:
        if (vitamin.equals("yes") && duber.equals("duber"))
        {
              System.out.println("During the party, the high levels of alcohol cause you to lose your mind and you wander out to the streets. You pick a fight with a passerby. Soon after, things get out of hand and you end up losing the fight badly. Eventually you pass away due to the force of the punches.");
            }
           break;
        case 2:
        if (vitamin.equals("yes") && duber.equals("duber"))
        {
              System.out.println("At the party, you start experiencing hallucinations that make you wander out in the busy street. One of the cars on the street was not able to stop fast enough and you were hit by a car and died on impact.");
            }
            break;
        case 3:
        if (vitamin.equals("yes") && duber.equals("duber"))
        {
              System.out.println("At the party, you put too much strain on yourself and you start to have a stroke. Because the other people at the party were also under the influence, you are unable to receive proper medical attention for your stroke and you pass away.");
            }
            break;
        case 4:
        if (vitamin.equals("yes") && duber.equals("duber"))
        {
              System.out.println("As you started to use cocaine more, you were more focused on cocaine than other natural needs such as food and water. You eventually die from malnutrition. ");
            }
            break;
        case 5:
        if (vitamin.equals("yes") && duber.equals("duber"))
        {
            System.out.println(" As you enter the party, you start to feel restless due to the insomnia you’ve been facing. You start to feel irregular pain in your kidney and liver and somehow get to a local hospital. The doctor diagnosed your pain as lung and kidney disease and took you to surgery immediately. You die from surgery complications.");
        }
           break;
        case 6:
        if (vitamin.equals("yes") && duber.equals("duber"))
        {
              System.out.println("While dancing at the party you suddenly feel a stiffness in your body. All of a sudden you lose consciousness and your arms and legs start jerking. You get a seizure from epilepsy. The prolonged use of Marijuana causes you to lose your life.");
            }
            break;
        case 7:
        if (vitamin.equals("yes") && duber.equals("duber"))
        {
              System.out.println("During the party, your breathing gets heavier and you suddenly get a panic attack. You run out of the house where the party is held and you get hit by a passing car. You die immediately upon impact.");
            }
            break;
        default:
            System.out.println("Please enter a number from 1-7.");
         }
    }
}
System.out.println();
switch (x)
     {
         case 1:
          System.out.println("You have reached the end of the game. Here are some of the effects of "+drug+":");
          System.out.println("-Alcohol slows down the central nervous system. This can lead to feelings of relaxation, confidence, or lowered inhibitions.");
          System.out.println("-It can cause physical reactions like loss of coordination, memory, and the ability to make good decisions (like drunk driving).");
          System.out.println("-Can make you more aggressive or emotional.");
          System.out.println("-Effects of a hangover can include: nausea and vomiting, headache, thirst, sensitivity to light and noise, diarrhoea, low mood and anxiety, bad memory.");
          System.out.println("-Alcohol dependence is common. Dependence on alcohol means that the user is likely to suffer withdrawal effects if they don’t drink.");
          System.out.println("-Addiction changes a person’s priorities, can be damaging to career and family.");
          System.out.println("-Organ Damage");
           break;
        case 2:
          System.out.println("You have reached the end of the game. Here are some of the effects of "+drug+":");
          System.out.println("Short-term effects: increased heart rate, nausea, intensified feelings and sensory experiences (such as seeing brighter colors), changes in sense of time (for example, the feeling that time is passing by slowly). increased blood pressure, breathing rate, or body temperature, loss of appetite, dry mouth, sleep problems, spiritual experiences, feelings of relaxation, uncoordinated movements, excessive sweating, panic");
          System.out.println("Long-term effects: visual disturbances, disorganized thinking, paranoia, mood changes.");
            break;
        case 3: 
           System.out.println("You have reached the end of the game. Here are some of the effects of "+drug+":");
           System.out.println("Short-term effects: Loss of appetite, Increased heart rate, blood pressure, body temperature, Dilation of pupils, Disturbed sleep patterns, Nausea, Bizarre or violent behavior, Hallucinations, irritability, Panic, Convulsions, seizures and death from high doses");
           System.out.println("Long-term effects: Permanent damage to blood vessels of heart and brain, heart attacks, strokes and death, Liver, kidney and lung damage, Destruction of tissues in nose if sniffed, Respiratory problems if smoked, Infectious diseases and abscesses if injected, Malnutrition, weight loss, Severe tooth decay, Strong psychological dependence, Depression, Damage to the brain similar to Alzheimer’s disease");
            break;
        case 4:
            System.out.println("You have reached the end of the game. Here are some of the effects of "+drug+":");
            System.out.println("Short-term effects: dilated pupils, and increased body temperature, heart rate, and blood pressure. Large amounts of cocaine can also lead to bizarre, erratic, and violent behavior. Feelings of restlessness, irritability, anxiety, and tremors");
            System.out.println("Long-term effects: increased displeasure and negative moods when not taking the drug, more likely to focus on seeking the drug instead of relationships, food, or other natural rewards.");
            break;
        case 5:
            System.out.println("You have reached the end of the game. Here are some of the effects of "+drug+":");
            System.out.println("Short-term effects: dry mouth, warm flushing of the skin, heavy feeling in the arms and legs, nausea and vomiting, severe itching, clouded mental functioning,a back-and-forth state of being conscious and not."); 
            System.out.println("Long-term effects: insomnia, collapsed veins, damaged tissue inside the nose for people who sniff it, infection of the heart lining and valves, swollen tissue filled with pus, constipation and stomach cramping, liver and kidney disease, lung complications, sexual dysfunction for men, irregular menstrual cycles for women.");
           break;
        case 6:
            System.out.println("You have reached the end of the game. Here are some of the effects of "+drug+":");
            System.out.println("lung damage, structural brain damage, heart attack, abuse of alcohol and other drugs, impaired capacity for learning, job loss and chronic unemployment, sexual dysfunction, legal problems, financial troublestrained, damaged, or ruined interpersonal relationships.");  
            break;
        case 7:
            System.out.println("You have reached the end of the game. Here are some of the effects of "+drug+":");
            System.out.println("Short-term effects: Bad breath, Fatigue, Reduction in the senses of taste and smell, Coughing, Shortness of breath.");
            System.out.println("Long-term effects: nicotine addiction, mood disorders, and permanent lowering of impulse control.");
            break;
        default:
            System.out.println("");
         
     }
     System.out.println();
     System.out.println("Play again to try to see how long you last or try a different number to get a different drug");
}
}
