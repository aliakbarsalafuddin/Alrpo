# mengambil nama sesuai yang di inputkan pada sistem menu 
    nama_topping = daftar_topping[topping]
    nama_crust = daftar_crust[crust]
    nama_ukuran = daftar_ukuran[ukuran]

    #deklarasi harga awal = 0 rupiah 
    harga = 0
    harga_topping = 43637 
    harga_xtracheese = 0
    
    # if untuk harga pizza dengan pinggiran crust pan dan juga harga per ukuranya ukurannya 
    if crust == 1 :
        hargacrust = 43637 # untuk harga pizza dengan pinggiran crust pan
        if ukuran == 1 :
            hargaukuran= 0 # untuk harga pizza dengan ukuran personal 
        elif ukuran == 2 :
            hargaukuran = 57273 # untuk harga pizza  dengan ukuran regural 
        else: 
            hargaukuran = 89091 # untuk harga pizza dengan ukuran large
    
    # if untuk harga pizza dengan pinggiran stuffedcrust cheese dan juga harga per ukurannya 
    elif crust == 2 :
        hargacrust = 55455 # untuk harga pizza dengan pinggiran stuffedcrust cheese 
        if ukuran == 1 :
            hargaukuran = 0 # untuk harga pizza  dengan ukuran personal 
        elif ukuran == 2 :
            hargaukuran = 64455 # untuk harga pizza  dengan ukuran regural 
        else: 
            hargaukuran = 104545 # untuk harga pizza  dengan ukuran large 
    
    # if untuk harga pizza dengan pinggiran stuffedcrust sausage dan juga harga per ukurannya 
    elif crust == 3 :
        hargacrust = 52728 # untuk harga pizza dengan pinggiran stuffedcrust sausage 
        if ukuran == 1 :
            hargaukuran = 0 # untuk harga pizza dengan ukuran personal
        elif ukuran == 2 :
            hargaukuran = 64545 # untuk harga pizza  dengan ukuran reguler 
        else:
            hargaukuran = 102727 # untuk harga pizza  dengan ukuran large
            
    # if untuk harga pizzza dengan pinggiran cheessy bites dan juga harga per ukurannya 
    elif crust == 4 :
        hargacrust = 55455 # untuk harga pizza dengan pinggiran cheessy bites 
        if ukuran == 1 : 
            hargaukuran = 0 # harga dengan ukuran personal 
        elif ukuran == 2 :
            hargaukuran= 65455 #harga dengan ukuran reguler 
        else:
            hargaukuran = 104545 # harga dengan ukuran large
