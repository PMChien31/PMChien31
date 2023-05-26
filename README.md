- 👋 Hi, I’m @PMChien31
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
PMChien31/PMChien31 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package assignment;

import java.io.Serializable;
import javax.swing.JOptionPane;

public class NhanVien implements Serializable{

    String maNhanVien;
    String hoVaTen;
    int tuoi;
    String gmail;
    int luong;
    String pb;

    public NhanVien() {
    }

    public String getMaNhanVien() {
        return maNhanVien;
    }

    public String getHoVaTen() {
        return hoVaTen;
    }

    public int getTuoi() {
        return tuoi;
    }

    public String getGmail() {
        return gmail;
    }

    public int getLuong() {
        return luong;
    }

    public String getPb() {
        return pb;
    }

    public NhanVien(String maNhanVien, String hoVaTen, int tuoi, String gmail, int luong, String pb) {
        this.maNhanVien = maNhanVien;
        this.hoVaTen = hoVaTen;
        this.tuoi = tuoi;
        this.gmail = gmail;
        this.luong = luong;
        this.pb = pb;
       
    }
 
}
