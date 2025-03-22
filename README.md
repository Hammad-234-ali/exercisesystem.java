# exercisesystem.java
import java.util.Arrays;
import java.util.List;

class ExerciseSystem {
    private List<String> exercises = Arrays.asList("Neck Stretch", "Back Stretch", "Hand Exercise");

    public void suggestExercises() {
        System.out.println("Suggested Exercises: " + exercises);
    }
}
