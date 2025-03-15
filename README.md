import java.util.stream.Stream;

public class UppercaseConverter {
    public static void main(String[] args) {
        // Create a stream of names
        Stream<String> names = Stream.of("aBc", "d", "ef");

        // Convert the stream of names to uppercase using map()
        Stream<String> uppercasedNames = names.map(String::toUpperCase);

        // Print the uppercased names
        uppercasedNames.forEach(System.out::println);
    }
}
