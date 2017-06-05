using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Windows.Forms;

namespace AppLogin
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {
            WsService.Service masuk = new WsService.Service();
            Boolean hasil;
            hasil = masuk.login((textBox1.Text), (textBox2.Text));
            if (hasil == true)
            {
                label3.Text = "Login Berhasil";
            }
            else
            {
                label3.Text = "Coba Lagi";
            }
        }
    }
}
