> Note: ...is talking this about me :smile:

<div style="display: flex; justify-content: center;">
  <table style="border: none;">
    <tr>
      <td style="border: none;">
        <a href="https://open.spotify.com/user/31qrfcn4zsw23an2cq4yw64mdw4u">
          <img src="https://pr3novatorem-7zb2.vercel.app/api/spotify" alt="Spotify Now Playing" />
        </a>
      </td>
      <td style="border: none;">
        <img src="https://github.com/user-attachments/assets/704d9a28-6aa3-4239-9382-d999d17db77f" alt="octocat-anime" width="150"/>
      </td>
    </tr>
  </table>
</div>

Hi, I'm [Majo](https://www.instagram.com/planito.banana?igsh=MXV6cjM1enVocDg1cw==) an artist and IT student from 
[Totonicapán, Guatemala](https://www.google.com/maps/place/Totonicap%C3%A1n/@14.9134296,-91.3641048,15.75z/data=!4m15!1m8!3m7!1s0x858ea40c21b85925:0xfdd4561134ae9faf!2sTotonicap%C3%A1n!3b1!8m2!3d14.9173402!4d-91.3613923!16zL20vMDM2cTIx!3m5!1s0x858ea40c21b85925:0xfdd4561134ae9faf!8m2!3d14.9173402!4d-91.3613923!16zL20vMDM2cTIx?entry=ttu) :guatemala:


<img src="https://github.com/user-attachments/assets/0af8f658-643a-4b88-8894-5e1e1837069f" alt="Majo banner" style="width: 100%;" />
<br>
<a href="https://www.linkedin.com/in/mar%C3%ADa-jos%C3%A9-baquiax-rodr%C3%ADguez-su?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank">
      <img src="https://img.icons8.com/fluent/48/000000/linkedin.png" alt="LinkedIn" style="width: 40px;"/>
    </a>
    <!-- TikTok -->
    <a href="https://www.tiktok.com/@planito.banana?_t=8oV7VbQwrW2&_r=1">
      <img src="https://img.icons8.com/fluent/48/000000/tiktok.png" alt="TikTok" style="width: 40px;"/>
    </a>
    <!-- Instagram -->
    <a href="https://www.instagram.com/planito.banana?igsh=MXV6cjM1enVocDg1cw==" target="_blank">
      <img src="https://img.icons8.com/fluent/48/000000/instagram-new.png" alt="Instagram" style="width: 40px;"/>
    </a>

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
