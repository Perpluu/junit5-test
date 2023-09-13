import org.junit.jupiter.api.BeforeEach;
import org.junit.jupiter.api.Test;

import static org.junit.jupiter.api.Assertions.*;

/**
 * This is a JUnit 5 test class to test the functionality of a sample class.
 */
public class SampleClassTest {

    private SampleClass sample;

    @BeforeEach
    void setUp() {
        // Create an instance of SampleClass before each test method.
        sample = new SampleClass();
    }

    /**
     * Test method to verify the addition of two positive numbers.
     */
    @Test
    void testAddPositiveNumbers() {
        int result = sample.add(3, 4);
        assertEquals(7, result, "Addition of positive numbers should return the correct sum.");
    }

    /**
     * Test method to verify the subtraction of two numbers.
     */
    @Test
    void testSubtractNumbers() {
        int result = sample.subtract(8, 3);
        assertEquals(5, result, "Subtraction of two numbers should return the correct difference.");
    }

    /**
     * Test method to check if a number is even.
     */
    @Test
    void testIsEven() {
        boolean even = sample.isEven(6);
        assertTrue(even, "The number 6 should be considered even.");
    }

    /**
     * Test method to check if a number is odd.
     */
    @Test
    void testIsOdd() {
        boolean odd = sample.isOdd(9);
        assertTrue(odd, "The number 9 should be considered odd.");
    }
}
