https://github.com/user-attachments/assets/c3cedf1e-264f-43de-9706-91bf2d71102e

<img align='right' src='![octocat-anime](https://github.com/user-attachments/assets/a1c9829f-9cc5-4cf2-b4be-bbadc5113715)' width='150"'>

> Note: ...is talking this about me :smile:

Hi, I'm [Majo](https://www.instagram.com/planito.banana?igsh=MXV6cjM1enVocDg1cw==) an artist and IT student from 
[Totonicapán, Guatemala](https://www.google.com/maps/place/Totonicap%C3%A1n/@14.9134296,-91.3641048,15.75z/data=!4m15!1m8!3m7!1s0x858ea40c21b85925:0xfdd4561134ae9faf!2sTotonicap%C3%A1n!3b1!8m2!3d14.9173402!4d-91.3613923!16zL20vMDM2cTIx!3m5!1s0x858ea40c21b85925:0xfdd4561134ae9faf!8m2!3d14.9173402!4d-91.3613923!16zL20vMDM2cTIx?entry=ttu) :guatemala:

### Playing 🎵:

[![Spotify](https://novatorem.bgstatic.vercel.app/api/spotify)](https://open.spotify.com/user/11153360645)

## Life:

 ```java
public class ArtisticBalance {

    /**
     * A method to balance your creative tasks and personal projects.
     *
     * @param task The task to execute.
     * @param theme Your current artistic theme. Default is 'Inspiration'.
     * @return A creative and engaging message.
     */
    public static String balanceCreativeTasks(String task, String theme) {
        // Artistic symbols
        String[] artisticElements = {
            "[Palette]", "[Brush]", "[Mask]", "[Music]"
        };

        // Creative advice based on theme
        String[] creativeAdvice = {
            "Embrace your inner artist and let your creativity flow!",
            "Keep experimenting with new ideas and techniques.",
            "Reflect on your past works to inspire your next masterpiece.",
            "Find beauty in every challenge you face."
        };

        // Themes available
        String[] themes = {
            "Inspiration", "Experimentation", "Reflection", "Challenge"
        };

        // Determine the index of the theme
        int themeIndex = -1;
        for (int i = 0; i < themes.length; i++) {
            if (themes[i].equalsIgnoreCase(theme)) {
                themeIndex = i;
                break;
            }
        }

        // Handle invalid theme
        if (themeIndex == -1) {
            return "Invalid theme! Please choose between 'Inspiration', 'Experimentation', 'Reflection', or 'Challenge'.";
        }

        // Select artistic element and advice
        String artisticElement = artisticElements[themeIndex % artisticElements.length];
        String advice = creativeAdvice[themeIndex % creativeAdvice.length];

        return String.format("Task to complete: %s %s. %nAdvice: %s", task, artisticElement, advice);
    }

    public static void main(String[] args) {
        // Example usage
        String message = balanceCreativeTasks("Complete painting project", "Inspiration");
        System.out.println(message);
    }
}

	
 ```
