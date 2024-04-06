
    ========================================================================
    Recap About Loop concept : for loop , while loop , Do while loop <Start>
    ========================================================================
    /**
    * To do : Loop : for loop , while loop , Do while , React ( Foreach, map , forin)
    * loop : repeated kaj er jonno use hoi loop 
    */

    for(let i =0; i < 20 ; i++){                           // i++ post increment 
        console.log(i,"Hello ModernFrontEnd Developer");   // ekane bar bar i er value reassign hocce. 
    }
    // ----------------------------------------------------------------
    /**
    * Namta : 10 er namta 
    * 10 * 1 = 10
    * 10 * 2 = 20
    */
    -------------------------
    let multiply = 10;
    for(let i = 1; i<=10; i++ ){
        let result = multiply * i;
        console.log(`${multiply} * ${i} = ${result}`); 

        // jekono variable value change hole backtick (dollar and second bracket) dit e hobe
    }
    /**output
    * 10 * 1 = 10
    10 * 2 = 20
    10 * 3 = 30
    10 * 4 = 40
    10 * 5 = 50
    10 * 6 = 60
    10 * 7 = 70
    10 * 8 = 80
    10 * 9 = 90
    10 * 10 = 100
    */
    // ============================================================
    // alternative way 
    /**
    * Namta : 10 er namta 
    * 10 * 1 = 10
    * 10 * 2 = 20
    */--------------------------------------------------------
    let input = prompt("Enter the multiplication table number")
    let namta = +input;

    for (let i = 1; i<=10 ; i++){
        console.log(namta + " X " + i + " = " + namta*i);
    }
    /**
    * output : 
    * 7 X 1 = 7
    7 X 2 = 14
    7 X 3 = 21
    7 X 4 = 28
    7 X 5 = 35
    7 X 6 = 42
    7 X 7 = 49
    7 X 8 = 56
    7 X 9 = 63
    7 X 10 = 70
    */
    // ============================================================
    // alternative way  to show in display
    /**
    * Namta : 10 er namta 
    * 10 * 1 = 10
    * 10 * 2 = 20
    */
    ------------------------------------------------------------------
    let inputs = prompt("Enter the multiplication table number")
    let namtas = +inputs;

    for (let i = 1; i<=10 ; i++){
        //console.log(namtas + " X " + i + " = " + namtas*i);
        document.write(namtas + " X " + i + " = " + namtas*i + "<br>") // just use br in string
    }
    // ============================================================
    // make 20 er namta in while loop //
    /**
    * 10 * 1 = 10
    * 
    */
    -------------------------------------------------------------------
    let i = 1 ;
    let count = 10;
    while (i <=10) {
        console.log(`${count} * ${i} = ${count* i}`);
        i++
    }
    // ============================================================
    /// make 25 er namta in do while loop
    -------------------------------------------------------------------
    let counts = 1;
    let statics = 25

    do{
        console.log(`${statics} * ${counts} = ${statics* counts}`);
        counts++
    }while(counts<=10)

    /**
    * 
    * 25 * 1 = 25
    25 * 2 = 50
    25 * 3 = 75
    25 * 4 = 100
    25 * 5 = 125
    25 * 6 = 150
    25 * 7 = 175
    25 * 8 = 200
    25 * 9 = 225
    25 * 10 = 250
    */
    ========================================================================
    Recap About Loop concept : for loop , while loop , Do while loop <End>
    ========================================================================