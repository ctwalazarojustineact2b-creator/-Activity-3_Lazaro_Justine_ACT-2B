//I Used programmiz as a compiler.


<?php
$name[100];
$cys[100];
$age[100];


echo "Enter your name: ";
$name = trim(fgets(STDIN));
echo "CYS : ";
$cys = trim(fgets(STDIN));
echo "Age: ";
$age = trim(fgets(STDIN));
echo "Your Information:, $name, $cys, $age \n";



echo "============================================";
echo "                 !YOUR GRADE!               ";
echo "============================================";
echo "\n";

$grade1 = 70;
$grade2 = 72;
$grade3 = 67;

$average = ($grade1 + $grade2 + $grade3) / 3;

echo "Grade 1: $grade1\n";
echo "Grade 2: $grade2\n";
echo "Grade 3: $grade3\n";
echo "Average: $average\n";

if ($average >= 74.5) {
    echo "Remark: Passed\n";
} else {
    echo "Remark: Failed\n";
}

if ($average >= 90 && $average <= 100) {
    echo "Letter Grade: A\n";
}
else if ($average >= 80) {
    echo "Letter Grade: B\n";
}
else if ($average >= 70) {
    echo "Letter Grade: C\n";
}
else if ($average >= 60) {
    echo "Letter Grade: D\n";
}
else {
    echo "Letter Grade: F\n";
}


?>
