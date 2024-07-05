# form-data-processor

corrige o código:
#pragma once

namespace CppCLRWinFormsProject {

    using namespace System;
    using namespace System::ComponentModel;
    using namespace System::Collections;
    using namespace System::Windows::Forms;
    using namespace System::Data;
    using namespace System::Drawing;

    /// <summary>
    /// Summary for Form1
    /// </summary>
    public ref class Form1 : public System::Windows::Forms::Form
    {
    public:
        Form1(void)
        {
            InitializeComponent();
            //
            //TODO: Add the constructor code here
            //
        }

    protected:
        /// <summary>
        /// Clean up any resources being used.
        /// </summary>
        ~Form1()
        {
            if (components)
            {
                delete components;
            }
        }
    private: System::Windows::Forms::TextBox^ txt_nome;
    private: System::Windows::Forms::TextBox^ txt_nota1;
    private: System::Windows::Forms::TextBox^ txt_nota2;
    private: System::Windows::Forms::TextBox^ txt_nota3;

    protected:

    protected:



    private: System::Windows::Forms::TextBox^ txt_processo;

    private: System::Windows::Forms::Label^ label1;
    private: System::Windows::Forms::Label^ label2;
    private: System::Windows::Forms::Label^ label3;
    private: System::Windows::Forms::Label^ label4;
    private: System::Windows::Forms::Label^ label5;
    private: System::Windows::Forms::ListBox^ lb_nome;
    private: System::Windows::Forms::ListBox^ lb_processo;
    private: System::Windows::Forms::ListBox^ lb_nota1;
    private: System::Windows::Forms::ListBox^ lb_nota3;




    private: System::Windows::Forms::ListBox^ lb_nota2;

    private: System::Windows::Forms::GroupBox^ groupBox1;


    private: System::Windows::Forms::TextBox^ txt_nota3_gb;

    private: System::Windows::Forms::TextBox^ txt_nota2_gb;

    private: System::Windows::Forms::TextBox^ txt_nota1_gb;


    private: System::Windows::Forms::Label^ label9;
    private: System::Windows::Forms::Label^ label8;
    private: System::Windows::Forms::Label^ label7;
    private: System::Windows::Forms::Label^ label6;
    private: System::Windows::Forms::TextBox^ txt_processo_gb;

    private: System::Windows::Forms::Button^ button3;
    private: System::Windows::Forms::Label^ label10;
    private: System::Windows::Forms::TextBox^ txt_nome_gb;
    private: System::Windows::Forms::Label^ label11;
    private: System::Windows::Forms::Button^ button1;
    private: System::Windows::Forms::Button^ button2;

    private:
        /// <summary>
        /// Required designer variable.
        /// </summary>
        System::ComponentModel::Container^ components;

#pragma region Windows Form Designer generated code
        /// <summary>
        /// Required method for Designer support - do not modify
        /// the contents of this method with the code editor.
        /// </summary>
        void InitializeComponent(void)
        {
            this->txt_nome = (gcnew System::Windows::Forms::TextBox());
            this->txt_nota1 = (gcnew System::Windows::Forms::TextBox());
            this->txt_nota2 = (gcnew System::Windows::Forms::TextBox());
            this->txt_nota3 = (gcnew System::Windows::Forms::TextBox());
            this->txt_processo = (gcnew System::Windows::Forms::TextBox());
            this->label1 = (gcnew System::Windows::Forms::Label());
            this->label2 = (gcnew System::Windows::Forms::Label());
            this->label3 = (gcnew System::Windows::Forms::Label());
            this->label4 = (gcnew System::Windows::Forms::Label());
            this->label5 = (gcnew System::Windows::Forms::Label());
            this->lb_nome = (gcnew System::Windows::Forms::ListBox());
            this->lb_processo = (gcnew System::Windows::Forms::ListBox());
            this->lb_nota1 = (gcnew System::Windows::Forms::ListBox());
            this->lb_nota3 = (gcnew System::Windows::Forms::ListBox());
            this->lb_nota2 = (gcnew System::Windows::Forms::ListBox());
            this->groupBox1 = (gcnew System::Windows::Forms::GroupBox());
            this->label10 = (gcnew System::Windows::Forms::Label());
            this->txt_nome_gb = (gcnew System::Windows::Forms::TextBox());
            this->button3 = (gcnew System::Windows::Forms::Button());
            this->txt_nota3_gb = (gcnew System::Windows::Forms::TextBox());
            this->txt_nota2_gb = (gcnew System::Windows::Forms::TextBox());
            this->txt_nota1_gb = (gcnew System::Windows::Forms::TextBox());
            this->label9 = (gcnew System::Windows::Forms::Label());
            this->label8 = (gcnew System::Windows::Forms::Label());
            this->label7 = (gcnew System::Windows::Forms::Label());
            this->label6 = (gcnew System::Windows::Forms::Label());
            this->txt_processo_gb = (gcnew System::Windows::Forms::TextBox());
            this->label11 = (gcnew System::Windows::Forms::Label());
            this->button1 = (gcnew System::Windows::Forms::Button());
            this->button2 = (gcnew System::Windows::Forms::Button());
            this->groupBox1->SuspendLayout();
            this->SuspendLayout();
            // 
            // txt_nome
            // 
            this->txt_nome->Location = System::Drawing::Point(34, 82);
            this->txt_nome->Name = L"txt_nome";
            this->txt_nome->Size = System::Drawing::Size(100, 20);
            this->txt_nome->TabIndex = 0;
            // 
            // txt_nota1
            // 
            this->txt_nota1->Location = System::Drawing::Point(350, 76);
            this->txt_nota1->Name = L"txt_nota1";
            this->txt_nota1->Size = System::Drawing::Size(100, 20);
            this->txt_nota1->TabIndex = 1;
            // 
            // txt_nota2
            // 
            this->txt_nota2->Location = System::Drawing::Point(508, 76);
            this->txt_nota2->Name = L"txt_nota2";
            this->txt_nota2->Size = System::Drawing::Size(100, 20);
            this->txt_nota2->TabIndex = 2;
            // 
            // txt_nota3
            // 
            this->txt_nota3->Location = System::Drawing::Point(660, 76);
            this->txt_nota3->Name = L"txt_nota3";
            this->txt_nota3->Size = System::Drawing::Size(100, 20);
            this->txt_nota3->TabIndex = 3;
            // 
            // txt_processo
            // 
            this->txt_processo->Location = System::Drawing::Point(188, 79);
            this->txt_processo->Name = L"txt_processo";
            this->txt_processo->Size = System::Drawing::Size(100, 20);
            this->txt_processo->TabIndex = 5;
            // 
            // label1
            // 
            this->label1->AutoSize = true;
            this->label1->Location = System::Drawing::Point(51, 34);
            this->label1->Name = L"label1";
            this->label1->Size = System::Drawing::Size(35, 13);
            this->label1->TabIndex = 6;
            this->label1->Text = L"Nome";
            // 
            // label2
            // 
            this->label2->AutoSize = true;
            this->label2->Location = System::Drawing::Point(202, 57);
            this->label2->Name = L"label2";
            this->label2->Size = System::Drawing::Size(51, 13);
            this->label2->TabIndex = 7;
            this->label2->Text = L"Processo";
            // 
            // label3
            // 
            this->label3->AutoSize = true;
            this->label3->Location = System::Drawing::Point(357, 34);
            this->label3->Name = L"label3";
            this->label3->Size = System::Drawing::Size(39, 13);
            this->label3->TabIndex = 8;
            this->label3->Text = L"Nota 1";
            // 
            // label4
            // 
            this->label4->AutoSize = true;
            this->label4->Location = System::Drawing::Point(522, 34);
            this->label4->Name = L"label4";
            this->label4->Size = System::Drawing::Size(39, 13);
            this->label4->TabIndex = 9;
            this->label4->Text = L"Nota 2";
            // 
            // label5
            // 
            this->label5->AutoSize = true;
            this->label5->Location = System::Drawing::Point(667, 34);
            this->label5->Name = L"label5";
            this->label5->Size = System::Drawing::Size(39, 13);
            this->label5->TabIndex = 10;
            this->label5->Text = L"Nota 3";
            // 
            // lb_nome
            // 
            this->lb_nome->FormattingEnabled = true;
            this->lb_nome->Location = System::Drawing::Point(32, 191);
            this->lb_nome->Name = L"lb_nome";
            this->lb_nome->Size = System::Drawing::Size(120, 147);
            this->lb_nome->TabIndex = 11;
            // 
            // lb_processo
            // 
            this->lb_processo->FormattingEnabled = true;
            this->lb_processo->Location = System::Drawing::Point(186, 191);
            this->lb_processo->Name = L"lb_processo";
            this->lb_processo->Size = System::Drawing::Size(120, 147);
            this->lb_processo->TabIndex = 12;
            // 
            // lb_nota1
            // 
            this->lb_nota1->FormattingEnabled = true;
            this->lb_nota1->Location = System::Drawing::Point(348, 191);
            this->lb_nota1->Name = L"lb_nota1";
            this->lb_nota1->Size = System::Drawing::Size(120, 147);
            this->lb_nota1->TabIndex = 13;
            // 
            // lb_nota3
            // 
            this->lb_nota3->FormattingEnabled = true;
            this->lb_nota3->Location = System::Drawing::Point(658, 191);
            this->lb_nota3->Name = L"lb_nota3";
            this->lb_nota3->Size = System::Drawing::Size(120, 147);
            this->lb_nota3->TabIndex = 14;
            // 
            // lb_nota2
            // 
            this->lb_nota2->FormattingEnabled = true;
            this->lb_nota2->Location = System::Drawing::Point(506, 191);
            this->lb_nota2->Name = L"lb_nota2";
            this->lb_nota2->Size = System::Drawing::Size(120, 147);
            this->lb_nota2->TabIndex = 15;
            // 
            // groupBox1
            // 
            this->groupBox1->Controls->Add(this->label10);
            this->groupBox1->Controls->Add(this->txt_nome_gb);
            this->groupBox1->Controls->Add(this->button3);
            this->groupBox1->Controls->Add(this->txt_nota3_gb);
            this->groupBox1->Controls->Add(this->txt_nota2_gb);
            this->groupBox1->Controls->Add(this->txt_nota1_gb);
            this->groupBox1->Controls->Add(this->label9);
            this->groupBox1->Controls->Add(this->label8);
            this->groupBox1->Controls->Add(this->label7);
            this->groupBox1->Controls->Add(this->label6);
            this->groupBox1->Controls->Add(this->txt_processo_gb);
            this->groupBox1->Location = System::Drawing::Point(848, 93);
            this->groupBox1->Name = L"groupBox1";
            this->groupBox1->Size = System::Drawing::Size(200, 301);
            this->groupBox1->TabIndex = 16;
            this->groupBox1->TabStop = false;
            this->groupBox1->Text = L"Atualizar Dados";
            this->groupBox1->Enter += gcnew System::EventHandler(this, &Form1::groupBox1_Enter);
            // 
            // label10
            // 
            this->label10->AutoSize = true;
            this->label10->Location = System::Drawing::Point(26, 85);
            this->label10->Name = L"label10";
            this->label10->Size = System::Drawing::Size(35, 13);
            this->label10->TabIndex = 11;
            this->label10->Text = L"Nome";
            // 
            // txt_nome_gb
            // 
            this->txt_nome_gb->Location = System::Drawing::Point(85, 78);
            this->txt_nome_gb->Name = L"txt_nome_gb";
            this->txt_nome_gb->Size = System::Drawing::Size(100, 20);
            this->txt_nome_gb->TabIndex = 10;
            // 
            // button3
            // 
            this->button3->Location = System::Drawing::Point(54, 250);
            this->button3->Name = L"button3";
            this->button3->Size = System::Drawing::Size(104, 23);
            this->button3->TabIndex = 9;
            this->button3->Text = L"Atualizar";
            this->button3->UseVisualStyleBackColor = true;
            this->button3->Click += gcnew System::EventHandler(this, &Form1::button3_Click);
            // 
            // txt_nota3_gb
            // 
            this->txt_nota3_gb->Location = System::Drawing::Point(85, 212);
            this->txt_nota3_gb->Name = L"txt_nota3_gb";
            this->txt_nota3_gb->Size = System::Drawing::Size(100, 20);
            this->txt_nota3_gb->TabIndex = 8;
            // 
            // txt_nota2_gb
            // 
            this->txt_nota2_gb->Location = System::Drawing::Point(85, 165);
            this->txt_nota2_gb->Name = L"txt_nota2_gb";
            this->txt_nota2_gb->Size = System::Drawing::Size(100, 20);
            this->txt_nota2_gb->TabIndex = 7;
            // 
            // txt_nota1_gb
            // 
            this->txt_nota1_gb->Location = System::Drawing::Point(85, 119);
            this->txt_nota1_gb->Name = L"txt_nota1_gb";
            this->txt_nota1_gb->Size = System::Drawing::Size(100, 20);
            this->txt_nota1_gb->TabIndex = 6;
            // 
            // label9
            // 
            this->label9->AutoSize = true;
            this->label9->Location = System::Drawing::Point(26, 219);
            this->label9->Name = L"label9";
            this->label9->Size = System::Drawing::Size(39, 13);
            this->label9->TabIndex = 5;
            this->label9->Text = L"Nota 3";
            // 
            // label8
            // 
            this->label8->AutoSize = true;
            this->label8->Location = System::Drawing::Point(26, 172);
            this->label8->Name = L"label8";
            this->label8->Size = System::Drawing::Size(39, 13);
            this->label8->TabIndex = 4;
            this->label8->Text = L"Nota 2";
            // 
            // label7
            // 
            this->label7->AutoSize = true;
            this->label7->Location = System::Drawing::Point(26, 126);
            this->label7->Name = L"label7";
            this->label7->Size = System::Drawing::Size(39, 13);
            this->label7->TabIndex = 3;
            this->label7->Text = L"Nota 1";
            // 
            // label6
            // 
            this->label6->AutoSize = true;
            this->label6->Location = System::Drawing::Point(82, 16);
            this->label6->Name = L"label6";
            this->label6->Size = System::Drawing::Size(51, 13);
            this->label6->TabIndex = 1;
            this->label6->Text = L"Processo";
            // 
            // txt_processo_gb
            // 
            this->txt_processo_gb->Location = System::Drawing::Point(54, 38);
            this->txt_processo_gb->Name = L"txt_processo_gb";
            this->txt_processo_gb->Size = System::Drawing::Size(104, 20);
            this->txt_processo_gb->TabIndex = 0;
            // 
            // label11
            // 
            this->label11->AutoSize = true;
            this->label11->Location = System::Drawing::Point(188, 33);
            this->label11->Name = L"label11";
            this->label11->Size = System::Drawing::Size(51, 13);
            this->label11->TabIndex = 17;
            this->label11->Text = L"Processo";
            // 
            // button1
            // 
            this->button1->Font = (gcnew System::Drawing::Font(L"Microsoft Sans Serif", 12, System::Drawing::FontStyle::Regular, System::Drawing::GraphicsUnit::Point,
                static_cast<System::Byte>(0)));
            this->button1->Location = System::Drawing::Point(358, 371);
            this->button1->Name = L"button1";
            this->button1->Size = System::Drawing::Size(90, 36);
            this->button1->TabIndex = 18;
            this->button1->Text = L"Sair";
            this->button1->UseVisualStyleBackColor = true;
            this->button1->Click += gcnew System::EventHandler(this, &Form1::button1_Click_2);
            // 
            // button2
            // 
            this->button2->Font = (gcnew System::Drawing::Font(L"Microsoft Sans Serif", 12, System::Drawing::FontStyle::Regular, System::Drawing::GraphicsUnit::Point,
                static_cast<System::Byte>(0)));
            this->button2->Location = System::Drawing::Point(360, 112);
            this->button2->Name = L"button2";
            this->button2->Size = System::Drawing::Size(90, 39);
            this->button2->TabIndex = 19;
            this->button2->Text = L"Registrar";
            this->button2->UseVisualStyleBackColor = true;
            this->button2->Click += gcnew System::EventHandler(this, &Form1::button2_Click_1);
            // 
            // Form1
            // 
            this->AutoScaleDimensions = System::Drawing::SizeF(6, 13);
            this->AutoScaleMode = System::Windows::Forms::AutoScaleMode::Font;
            this->ClientSize = System::Drawing::Size(1082, 506);
            this->Controls->Add(this->button2);
            this->Controls->Add(this->button1);
            this->Controls->Add(this->label11);
            this->Controls->Add(this->groupBox1);
            this->Controls->Add(this->lb_nota2);
            this->Controls->Add(this->lb_nota3);
            this->Controls->Add(this->lb_nota1);
            this->Controls->Add(this->lb_processo);
            this->Controls->Add(this->lb_nome);
            this->Controls->Add(this->label5);
            this->Controls->Add(this->label4);
            this->Controls->Add(this->label3);
            this->Controls->Add(this->txt_nota3);
            this->Controls->Add(this->txt_nota2);
            this->Controls->Add(this->txt_nota1);
            this->Controls->Add(this->txt_processo);
            this->Controls->Add(this->txt_nome);
            this->Controls->Add(this->label1);
            this->Name = L"Form1";
            this->Text = L"Form1";
            this->Load += gcnew System::EventHandler(this, &Form1::Form1_Load);
            this->groupBox1->ResumeLayout(false);
            this->groupBox1->PerformLayout();
            this->ResumeLayout(false);
            this->PerformLayout();

        }
#pragma endregion
    private: System::Void button1_Click(System::Object^ sender, System::EventArgs^ e) {
        lb_nome->Items->Add(txt_nome->Text);
        lb_processo->Items->Add(txt_processo->Text);
        lb_nota1->Items->Add(txt_nota1->Text);
        lb_nota2->Items->Add(txt_nota2->Text);
        lb_nota3->Items->Add(txt_nota3->Text);
    }
    private: System::Void button2_Click(System::Object^ sender, System::EventArgs^ e) {
       
    }
    private: System::Void button3_Click(System::Object^ sender, System::EventArgs^ e) {
        if (lb_nome->SelectedIndex != -1) {
            lb_nome->Items[lb_nome->SelectedIndex] = txt_nome_gb->Text;
            lb_processo->Items[lb_nome->SelectedIndex] = txt_processo_gb->Text;
            lb_nota1->Items[lb_nome->SelectedIndex] = txt_nota1_gb->Text;
            lb_nota2->Items[lb_nome->SelectedIndex] = txt_nota2_gb->Text;
            lb_nota3->Items[lb_nome->SelectedIndex] = txt_nota3_gb->Text;
        }
    }
    private: System::Void Form1_Load(System::Object^ sender, System::EventArgs^ e) {
    }
    private: System::Void button1_Click_1(System::Object^ sender, System::EventArgs^ e) {
    }
private: System::Void groupBox1_Enter(System::Object^ sender, System::EventArgs^ e) {
}
private: System::Void button2_Click_1(System::Object^ sender, System::EventArgs^ e) {

}
private: System::Void button1_Click_2(System::Object^ sender, System::EventArgs^ e) {
}
};
}



## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Tech stack

This project is built with .

- Vite
- React
- shadcn-ui
- Tailwind CSS

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/form-data-processor.git
cd form-data-processor
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
