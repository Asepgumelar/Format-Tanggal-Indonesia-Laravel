     <h1> Format Tanggal Indonesia</h1>
     
     /* Format Date
     variable = \Carbon\Carbon::now()->locale('id')->isoFormat('LLL');
                    return : 3 Juli 2020 pukul 15.17
     variable = \Carbon\Carbon::now()->locale('id')->isoFormat('LL');
                    return : 3 Juli 2020
     variable = \Carbon\Carbon::now()->locale('id')->isoFormat('LLLL');
                    return : Senin, 1 Mei 1945 pukul 21.00
     variable = \Carbon\Carbon::now()->locale('id')->isoFormat('dddd, Do MMMM YYYY, hh:mm');
                    return : Jumat, 3 Juli 2020, 03:19
     variable = \Carbon\Carbon::now()->locale('id')->isoFormat('dddd, Do MMMM YYYY, hh:mm:ss');
                    return : Jumat, 3 Juli 2020, 03:19:01
     */

    /* If Using Variable
     function ($date){
         \Carbon\Carbon::parse($date).........
     }
     */
