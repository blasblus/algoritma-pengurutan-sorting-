<?php
// List Item 
$list = array(2, 3, 6, 6, 2, 8, 4, 7);

// Menampilkan Item yang belum terurut
echo "Data Sebelum diurutkan </br>";
for ($i = 0; $i < count($list); $i++) {
    echo "$list[$i] ";
}

// Algoritma pengurutan Bubble Sort Ascending
for ($i = count($list) - 1; $i >= 0; $i--) {
    for ($j = 0; $j < $i; $j++) {
        if ($list[$j] > $list[$j + 1]) {
            $temp         = $list[$j];
            $list[$j]     = $list[$j + 1];
            $list[$j + 1] = $temp;
        }
    }
}

// Menampilkan Item yang telah terurut
echo "</br> Data Setelah diurutkan </br>";
for ($i = 0; $i < count($list); $i++) {
    echo "$list[$i] ";
}
?>
