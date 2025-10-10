# Hi, I'm Majo an artist and IT student from [Suchitepéquez, Guatemala](https://www.google.com/maps/place/Suchitep%C3%A9quez/@14.3752308,-91.7104978,10z/data=!3m1!4b1!4m6!3m5!1s0x85892c4c38a67de9:0xe5ee76e8a509c4ec!8m2!3d14.4215982!4d-91.4048249!16zL20vMDM2cF8w?entry=ttu&g_ep=EgoyMDI1MDcyMy4wIKXMDSoASAFQAw%3D%3D) :guatemala:

> Note: **"Never stop learning"** :smile:

### Visit my Projects Documentation and Landing Page

<p align="center">
  <a href="https://be00wulf.github.io/mj-ba.github.io/" target="_blank">
    <img src="https://raw.githubusercontent.com/Be00wulf/Be00wulf/main/img/gif%20landing.gif" alt="Landing Page" width="300px">
  </a>
</p>

| Currently Listening | Mood |
|----------|---------|
| [![Spotify](https://pr3novatorem-7zb2.vercel.app/api/spotify)](https://open.spotify.com/user/31qrfcn4zsw23an2cq4yw64mdw4u) | <img src="https://github.com/user-attachments/assets/704d9a28-6aa3-4239-9382-d999d17db77f" alt="octocat-anime" width="300"/> |

<img src="https://github.com/user-attachments/assets/0af8f658-643a-4b88-8894-5e1e1837069f" alt="Majo banner" width="100%"/>

## Life:

 ```java
import java.util.*;

public class ArtisticBalance {

    private static class ArtisticData {
        String element;
        String advice;

        ArtisticData(String element, String advice) {
            this.element = element;
            this.advice = advice;
        }
    }

    private static final Map<String, ArtisticData> THEMES = new HashMap<>();
    private static final Random RANDOM = new Random();

    static {
        THEMES.put("Drawing", new ArtisticData("[Pencil]", "Sketch daily to sharpen your observation skills."));
        THEMES.put("Painting", new ArtisticData("[Palette]", "Play with colors—don't be afraid to mix unexpected shades."));
        THEMES.put("Literature", new ArtisticData("[Book]", "Write something short today; even a single line counts."));
        THEMES.put("Music", new ArtisticData("[Note]", "Listen to new genres and try to replicate their rhythm."));
    }

    public static String balanceCreativeTasks(String task, String theme) {
        ArtisticData data = THEMES.get(theme);

        if (data == null) {
            List<String> keys = new ArrayList<>(THEMES.keySet());
            String randomTheme = keys.get(RANDOM.nextInt(keys.size()));
            data = THEMES.get(randomTheme);
            return String.format(
                "Task: %s %s%nAdvice (Theme: %s): %s",
                task, data.element, randomTheme, data.advice
            );
        }

        return String.format("Task: %s %s%nAdvice: %s", task, data.element, data.advice);
    }

    public static void main(String[] args) {
        System.out.println(balanceCreativeTasks("Work on creative projects", null));
        System.out.println(balanceCreativeTasks("Write a poem", "Literature"));
        System.out.println(balanceCreativeTasks("Practice piano", "Music"));
    }
}
 ```

### :zap: Recent activity 
<!--RECENT_ACTIVITY:start-->
1. ⬆️ Pushed 1 commit(s) to [Be00wulf/TTT_cs](https://github.com/Be00wulf/TTT_cs)<br>
2. ⬆️ Pushed 1 commit(s) to [Be00wulf/mj-ba.github.io](https://github.com/Be00wulf/mj-ba.github.io)<br>
3. ⬆️ Pushed 1 commit(s) to [Be00wulf/mj-ba.github.io](https://github.com/Be00wulf/mj-ba.github.io)<br>
4. ⬆️ Pushed 1 commit(s) to [Be00wulf/mj-ba.github.io](https://github.com/Be00wulf/mj-ba.github.io)<br>
5. ⬆️ Pushed 1 commit(s) to [Be00wulf/mj-ba.github.io](https://github.com/Be00wulf/mj-ba.github.io)<br>
<!--RECENT_ACTIVITY:end-->
<!--RECENT_ACTIVITY:last_update-->
Last Updated: Friday, October 10th, 2025, 1:52:30 AM
<!--RECENT_ACTIVITY:last_update_end-->
