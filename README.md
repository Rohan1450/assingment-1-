
# assingment-1
Q1 Write a program to print Hello Students on the screen.
print("Hello Students")
output : Hello Students 
Q2 Write a program to print Hello in the first line and Students in the second line.
print("Hello")
print("Students")
output : Hello 
        students
Q3 Write a program to print “iNeuron” on the screen. (Remember to print in double quotes)
print("iNueron")
output ; iNeuron
Q4 WAP to find the area of the circle. Take radius of circle from user as input and print the result in
below given format.
Expected output format – “Area of circle is A having the radius R”. Replace A with area
& R with radius.
# Take radius as input from the user
radius = float(input("Enter the radius of the circle: "))
# Calculate the area of the circle
area = math.pi * (radius ** 2)
# Print the result in the desired format
print(f'Area of circle is {area:.2f} having the radius {radius}')
output : Area of circle is 78.54 having the radius 5.0
Q5 WAP to calculate the length of String using printf function.
# Take a string input from the user
input_string = input("Enter a string: ")
# Calculate the length of the string
length_of_string = len(input_string)
# Print the length using formatted output
print("The length of the string is %d" % length_of_string)
output : The length of the string is 5
Q6 WAP to print the name of the user in double quotes.
Expected output format – “Hello , Amit Kumar”
# Define the user's name
user_name = "Amit Kumar"
# Print the greeting with the user's name in double quotes
print(f'\"Hello , {user_name}\"')
Q7 WAP to print “%d” on the screen.
int main() {
    std::cout << "%d" << std::endl;  // Print "%d" followed by a newline
    return 0;
}
Output ; '%d'
Q8 WAP to print “\n” on the screen.
int main() {
    std::cout << "\\n" << std::endl;  // Use \\ to escape the backslash and print "\n"
    return 0;
}
output : '\\'
Q9 WAP to print “\\” on the screen.
int main() {
    printf("\\\\");
    return 0;
}
output : '\\\\'
Q10 WAP to take date as an input in below given format and convert the date format and
display the result as given below.
User Input date format – “DD/MM/YYYY” (27/11/2022)
Output format –
“Day – DD , Month – MM , Year – YYYY” (Day – 27 ,Month – 07 , Year – 2022)
int main() {
    int day, month, year;
     // Prompting the user to input the date in "DD/MM/YYYY" format
    printf("Enter the date in format DD/MM/YYYY: ");
    scanf("%d/%d/%d", &day, &month, &year);

    // Displaying the date in the desired output format
    printf("Day – %02d, Month – %02d, Year – %d\n", day, month, year);

    return 0;
}
ouput ; Day – 27 , Month – 07 , Year – 2022
Q11 WAP to take time as an input in below given format and convert the time format and
display the result as given below.
User Input date format – “HH:MM”
Output format – “HH hour and MM Minute”
Example –
“11:25” converted to “11 Hour and 25 Minute”
12. Find output of below code:
int main()
{
int x = printf(“ineuron”);
printf(“%d”,x);
1. Program to Convert Time Format:
int main() {
    int hour, minute;
    // Taking time input in HH:MM format
    printf("Enter the time in HH:MM format: ");
    scanf("%d:%d", &hour, &minute);
    // Printing the time in the desired format
    printf("%02d Hour and %02d Minute\n", hour, minute);
    return 0;
}
output ; 11 Hour and 25 Minute
2. Output of the Given Code:
int main() 
{
    int x = printf("ineuron");
    printf("%d", x);
    return 0;
}
output ; ineuron7


