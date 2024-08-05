### Playing ⏯️

<div style="display: flex; justify-content: center;">
  <table style="border: none;">
    <tr>
      <td style="border: none;">
        <a href="https://open.spotify.com/user/31qrfcn4zsw23an2cq4yw64mdw4u">
          <img src="https://pr3novatorem-7zb2.vercel.app/api/spotify" alt="Spotify Now Playing" />
        </a>
      </td>
      <td style="border: none;">
        <img src="https://github.com/user-attachments/assets/704d9a28-6aa3-4239-9382-d999d17db77f" alt="octocat-anime" width="300"/>
      </td>
    </tr>
  </table>
</div>


> Note: ...is talking this about me :smile:

Hi, I'm [Majo](https://www.instagram.com/planito.banana?igsh=MXV6cjM1enVocDg1cw==) an artist and IT student from 
[Totonicapán, Guatemala](https://www.google.com/maps/place/Totonicap%C3%A1n/@14.9134296,-91.3641048,15.75z/data=!4m15!1m8!3m7!1s0x858ea40c21b85925:0xfdd4561134ae9faf!2sTotonicap%C3%A1n!3b1!8m2!3d14.9173402!4d-91.3613923!16zL20vMDM2cTIx!3m5!1s0x858ea40c21b85925:0xfdd4561134ae9faf!8m2!3d14.9173402!4d-91.3613923!16zL20vMDM2cTIx?entry=ttu) :guatemala:

![Github Banner](https://github.com/user-attachments/assets/0af8f658-643a-4b88-8894-5e1e1837069f)

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
