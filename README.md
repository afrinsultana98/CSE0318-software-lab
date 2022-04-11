# CSE0318-software-lab
project is income tax and car tax

code segment
package practice;
public class practice extends javax.swing.JFrame {
    double  tai,ttai1,ttai2,ttai3,ttai4,ttai5,a,b,c,d,e,ttax,TC,TAX,ali,TAI,car=0;
    int initialvalue=0;
    private int initialValue;
public practice() {
        initComponents();
         initialSetValue();
    }
 void initialSetValue(){
      BS.setText(0+"");
     HRA.setText(0+"");
  MA.setText(0+"");
    CA.setText(0+"");
 LI.setText(0+"");
    PF.setText(0+"");
  PFB.setText(0+"");
   LF.setText(0+"");
  OB.setText(0+"");
    SP.setText(0+"");
    FB.setText(0+"");
    SM.setText(0+"");
   OI.setText(0+"");
    LI.setText(0+"");
    GS.setText(0+"");
    OB1.setText(0+"");
    CALCULATE.setText(0+"");
     TAXABLEINCOME.setText(0+"");
     CALCULATE1.setText(0+"");
      test.setText(0+" ");
 }
    @SuppressWarnings("unchecked")
    // <editor-fold defaultstate="collapsed" desc="Generated Code">                          
    private void initComponents() {

        jPanel5 = new javax.swing.JPanel();
        jLabel2 = new javax.swing.JLabel();
        jLabel5 = new javax.swing.JLabel();
        jLabel6 = new javax.swing.JLabel();
        jLabel7 = new javax.swing.JLabel();
        jLabel9 = new javax.swing.JLabel();
        BS = new javax.swing.JTextField();
        HRA = new javax.swing.JTextField();
        CA = new javax.swing.JTextField();
        MA = new javax.swing.JTextField();
        jLabel17 = new javax.swing.JLabel();
        GS = new javax.swing.JTextField();
        jPanel4 = new javax.swing.JPanel();
        LI = new javax.swing.JTextField();
        SP = new javax.swing.JTextField();
        SM = new javax.swing.JTextField();
        OI = new javax.swing.JTextField();
        jLabel13 = new javax.swing.JLabel();
        jLabel15 = new javax.swing.JLabel();
        jLabel16 = new javax.swing.JLabel();
        jLabel14 = new javax.swing.JLabel();
        jLabel4 = new javax.swing.JLabel();
        jPanel6 = new javax.swing.JPanel();
        jLabel3 = new javax.swing.JLabel();
        jLabel1 = new javax.swing.JLabel();
        jLabel8 = new javax.swing.JLabel();
        jLabel10 = new javax.swing.JLabel();
        jLabel11 = new javax.swing.JLabel();
        FB = new javax.swing.JTextField();
        PF = new javax.swing.JTextField();
        PFB = new javax.swing.JTextField();
        LF = new javax.swing.JTextField();
        OB = new javax.swing.JTextField();
        jLabel12 = new javax.swing.JLabel();
        jLabel20 = new javax.swing.JLabel();
        jLabel21 = new javax.swing.JLabel();
        OB1 = new javax.swing.JTextField();
        jPanel1 = new javax.swing.JPanel();
        jLabel18 = new javax.swing.JLabel();
        exit = new javax.swing.JButton();
        reset = new javax.swing.JButton();
        jLabel19 = new javax.swing.JLabel();
        taxcredit = new javax.swing.JLabel();
        jButton2 = new javax.swing.JButton();
        CALCULATE = new javax.swing.JTextField();
        test = new javax.swing.JTextField();
        TAXABLEINCOME = new javax.swing.JTextField();
        jButton3 = new javax.swing.JButton();
        CALCULATE1 = new javax.swing.JTextField();

        setDefaultCloseOperation(javax.swing.WindowConstants.EXIT_ON_CLOSE);

        jPanel5.setBackground(new java.awt.Color(0, 0, 60,100));

        jLabel2.setFont(new java.awt.Font("Tahoma", 1, 18)); // NOI18N
        jLabel2.setText("Salary");

        jLabel5.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        jLabel5.setText("Basic Salary");

        jLabel6.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        jLabel6.setText("House Rent Allowance");

        jLabel7.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        jLabel7.setText("Conveyance Allowance");

        jLabel9.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        jLabel9.setText("Medical Allowance");

        BS.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        BS.addFocusListener(new java.awt.event.FocusAdapter() {
            public void focusGained(java.awt.event.FocusEvent evt) {
                BSFocusGained(evt);
            }
            public void focusLost(java.awt.event.FocusEvent evt) {
                BSFocusLost(evt);
            }
        });
        BS.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                BSActionPerformed(evt);
            }
        });

        HRA.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        HRA.addFocusListener(new java.awt.event.FocusAdapter() {
            public void focusGained(java.awt.event.FocusEvent evt) {
                HRAFocusGained(evt);
            }
            public void focusLost(java.awt.event.FocusEvent evt) {
                HRAFocusLost(evt);
            }
        });
        HRA.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                HRAActionPerformed(evt);
            }
        });

        CA.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        CA.addFocusListener(new java.awt.event.FocusAdapter() {
            public void focusGained(java.awt.event.FocusEvent evt) {
                CAFocusGained(evt);
            }
            public void focusLost(java.awt.event.FocusEvent evt) {
                CAFocusLost(evt);
            }
        });
        CA.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                CAActionPerformed(evt);
            }
        });

        MA.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        MA.addFocusListener(new java.awt.event.FocusAdapter() {
            public void focusGained(java.awt.event.FocusEvent evt) {
                MAFocusGained(evt);
            }
            public void focusLost(java.awt.event.FocusEvent evt) {
                MAFocusLost(evt);
            }
        });
        MA.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                MAActionPerformed(evt);
            }
        });

        jLabel17.setFont(new java.awt.Font("Tahoma", 1, 14)); // NOI18N
        jLabel17.setForeground(new java.awt.Color(0, 102, 0));
        jLabel17.setText("Gross Salary");

        GS.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        GS.addFocusListener(new java.awt.event.FocusAdapter() {
            public void focusGained(java.awt.event.FocusEvent evt) {
                GSFocusGained(evt);
            }
            public void focusLost(java.awt.event.FocusEvent evt) {
                GSFocusLost(evt);
            }
        });
        GS.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                GSActionPerformed(evt);
            }
        });

        jPanel4.setBackground(new java.awt.Color(0, 0, 60,0));

        LI.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        LI.addFocusListener(new java.awt.event.FocusAdapter() {
            public void focusGained(java.awt.event.FocusEvent evt) {
                LIFocusGained(evt);
            }
            public void focusLost(java.awt.event.FocusEvent evt) {
                LIFocusLost(evt);
            }
        });
        LI.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                LIActionPerformed(evt);
            }
        });

        SP.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        SP.addFocusListener(new java.awt.event.FocusAdapter() {
            public void focusGained(java.awt.event.FocusEvent evt) {
                SPFocusGained(evt);
            }
            public void focusLost(java.awt.event.FocusEvent evt) {
                SPFocusLost(evt);
            }
        });
        SP.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                SPActionPerformed(evt);
            }
        });

        SM.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        SM.addFocusListener(new java.awt.event.FocusAdapter() {
            public void focusGained(java.awt.event.FocusEvent evt) {
                SMFocusGained(evt);
            }
            public void focusLost(java.awt.event.FocusEvent evt) {
                SMFocusLost(evt);
            }
        });
        SM.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                SMActionPerformed(evt);
            }
        });

        OI.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        OI.addFocusListener(new java.awt.event.FocusAdapter() {
            public void focusGained(java.awt.event.FocusEvent evt) {
                OIFocusGained(evt);
            }
            public void focusLost(java.awt.event.FocusEvent evt) {
                OIFocusLost(evt);
            }
        });
        OI.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                OIActionPerformed(evt);
            }
        });

        jLabel13.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        jLabel13.setText("Sanchoypatra");

        jLabel15.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        jLabel15.setText("Share Market");

        jLabel16.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        jLabel16.setText("Life Insurance");

        jLabel14.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        jLabel14.setText("Other Investment");

        jLabel4.setFont(new java.awt.Font("Tahoma", 1, 18)); // NOI18N
        jLabel4.setText("Allowable Investment");

        javax.swing.GroupLayout jPanel4Layout = new javax.swing.GroupLayout(jPanel4);
        jPanel4.setLayout(jPanel4Layout);
        jPanel4Layout.setHorizontalGroup(
            jPanel4Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(jPanel4Layout.createSequentialGroup()
                .addGroup(jPanel4Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, jPanel4Layout.createSequentialGroup()
                        .addGap(2, 2, 2)
                        .addComponent(jLabel16)
                        .addGap(41, 41, 41))
                    .addGroup(jPanel4Layout.createSequentialGroup()
                        .addGroup(jPanel4Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addComponent(jLabel14)
                            .addGroup(jPanel4Layout.createSequentialGroup()
                                .addGap(2, 2, 2)
                                .addComponent(jLabel13))
                            .addComponent(jLabel15))
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)))
                .addGroup(jPanel4Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING, false)
                    .addComponent(SP, javax.swing.GroupLayout.DEFAULT_SIZE, 90, Short.MAX_VALUE)
                    .addComponent(SM, javax.swing.GroupLayout.Alignment.LEADING)
                    .addComponent(OI, javax.swing.GroupLayout.Alignment.LEADING)
                    .addComponent(LI))
                .addContainerGap(javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
            .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, jPanel4Layout.createSequentialGroup()
                .addGap(0, 40, Short.MAX_VALUE)
                .addComponent(jLabel4)
                .addGap(38, 38, 38))
        );
        jPanel4Layout.setVerticalGroup(
            jPanel4Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(jPanel4Layout.createSequentialGroup()
                .addContainerGap()
                .addComponent(jLabel4)
                .addGap(112, 112, 112)
                .addGroup(jPanel4Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(jLabel16)
                    .addComponent(LI, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(24, 24, 24)
                .addGroup(jPanel4Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(jLabel13)
                    .addComponent(SP, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(23, 23, 23)
                .addGroup(jPanel4Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(jLabel15)
                    .addComponent(SM, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(25, 25, 25)
                .addGroup(jPanel4Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(OI, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(jLabel14))
                .addContainerGap(110, Short.MAX_VALUE))
        );

        jPanel6.setBackground(new java.awt.Color(0, 0, 0,0));

        jLabel3.setFont(new java.awt.Font("Tahoma", 1, 18)); // NOI18N
        jLabel3.setText("Benifits from Office");

        jLabel1.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        jLabel1.setText("Festival Bonus");

        jLabel8.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        jLabel8.setText("Provident Found");

        jLabel10.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        jLabel10.setText("Performance Bonus");

        jLabel11.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        jLabel11.setText("Leave Fare");

        FB.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        FB.addFocusListener(new java.awt.event.FocusAdapter() {
            public void focusGained(java.awt.event.FocusEvent evt) {
                FBFocusGained(evt);
            }
            public void focusLost(java.awt.event.FocusEvent evt) {
                FBFocusLost(evt);
            }
        });
        FB.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                FBActionPerformed(evt);
            }
        });

        PF.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        PF.addFocusListener(new java.awt.event.FocusAdapter() {
            public void focusGained(java.awt.event.FocusEvent evt) {
                PFFocusGained(evt);
            }
            public void focusLost(java.awt.event.FocusEvent evt) {
                PFFocusLost(evt);
            }
        });
        PF.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                PFActionPerformed(evt);
            }
        });

        PFB.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        PFB.addFocusListener(new java.awt.event.FocusAdapter() {
            public void focusGained(java.awt.event.FocusEvent evt) {
                PFBFocusGained(evt);
            }
            public void focusLost(java.awt.event.FocusEvent evt) {
                PFBFocusLost(evt);
            }
        });
        PFB.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                PFBActionPerformed(evt);
            }
        });

        LF.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        LF.addFocusListener(new java.awt.event.FocusAdapter() {
            public void focusGained(java.awt.event.FocusEvent evt) {
                LFFocusGained(evt);
            }
            public void focusLost(java.awt.event.FocusEvent evt) {
                LFFocusLost(evt);
            }
        });
        LF.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                LFActionPerformed(evt);
            }
        });

        OB.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        OB.addFocusListener(new java.awt.event.FocusAdapter() {
            public void focusGained(java.awt.event.FocusEvent evt) {
                OBFocusGained(evt);
            }
            public void focusLost(java.awt.event.FocusEvent evt) {
                OBFocusLost(evt);
            }
        });
        OB.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                OBActionPerformed(evt);
            }
        });

        jLabel12.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        jLabel12.setText("Others Benifits");

        jLabel21.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        jLabel21.setText("Car CC");

        OB1.setFont(new java.awt.Font("Tahoma", 0, 14)); // NOI18N
        OB1.addFocusListener(new java.awt.event.FocusAdapter() {
            public void focusGained(java.awt.event.FocusEvent evt) {
                OB1FocusGained(evt);
            }
            public void focusLost(java.awt.event.FocusEvent evt) {
                OB1FocusLost(evt);
            }
        });
        OB1.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                OB1ActionPerformed(evt);
            }
        });

        javax.swing.GroupLayout jPanel6Layout = new javax.swing.GroupLayout(jPanel6);
        jPanel6.setLayout(jPanel6Layout);
        jPanel6Layout.setHorizontalGroup(
            jPanel6Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(jPanel6Layout.createSequentialGroup()
                .addGroup(jPanel6Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING, false)
                    .addGroup(jPanel6Layout.createSequentialGroup()
                        .addComponent(jLabel10)
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                        .addComponent(PFB, javax.swing.GroupLayout.PREFERRED_SIZE, 91, javax.swing.GroupLayout.PREFERRED_SIZE))
                    .addGroup(jPanel6Layout.createSequentialGroup()
                        .addGroup(jPanel6Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addComponent(jLabel1)
                            .addComponent(jLabel12)
                            .addComponent(jLabel8)
                            .addGroup(jPanel6Layout.createSequentialGroup()
                                .addContainerGap()
                                .addComponent(jLabel21)))
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                        .addGroup(jPanel6Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, jPanel6Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                                .addComponent(jLabel20)
                                .addComponent(FB, javax.swing.GroupLayout.Alignment.TRAILING, javax.swing.GroupLayout.PREFERRED_SIZE, 91, javax.swing.GroupLayout.PREFERRED_SIZE))
                            .addComponent(PF, javax.swing.GroupLayout.Alignment.TRAILING, javax.swing.GroupLayout.PREFERRED_SIZE, 91, javax.swing.GroupLayout.PREFERRED_SIZE)
                            .addComponent(OB, javax.swing.GroupLayout.Alignment.TRAILING, javax.swing.GroupLayout.PREFERRED_SIZE, 91, javax.swing.GroupLayout.PREFERRED_SIZE)
                            .addComponent(OB1, javax.swing.GroupLayout.PREFERRED_SIZE, 91, javax.swing.GroupLayout.PREFERRED_SIZE)))
                    .addGroup(jPanel6Layout.createSequentialGroup()
                        .addComponent(jLabel11)
                        .addGap(194, 194, 194)
                        .addComponent(LF, javax.swing.GroupLayout.PREFERRED_SIZE, 91, javax.swing.GroupLayout.PREFERRED_SIZE))
                    .addGroup(javax.swing.GroupLayout.Alignment.LEADING, jPanel6Layout.createSequentialGroup()
                        .addGap(88, 88, 88)
                        .addComponent(jLabel3)))
                .addContainerGap(32, Short.MAX_VALUE))
        );
        jPanel6Layout.setVerticalGroup(
            jPanel6Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(jPanel6Layout.createSequentialGroup()
                .addContainerGap()
                .addComponent(jLabel3)
                .addGap(37, 37, 37)
                .addGroup(jPanel6Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(jLabel1)
                    .addComponent(FB, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(34, 34, 34)
                .addGroup(jPanel6Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(jLabel8)
                    .addComponent(PF, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(24, 24, 24)
                .addGroup(jPanel6Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(jLabel10)
                    .addComponent(PFB, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(18, 18, 18)
                .addGroup(jPanel6Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(jLabel11)
                    .addComponent(LF, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)
                .addGroup(jPanel6Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(jLabel12)
                    .addComponent(OB, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(59, 59, 59)
                .addComponent(jLabel20)
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                .addGroup(jPanel6Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(OB1, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(jLabel21))
                .addContainerGap(19, Short.MAX_VALUE))
        );

        javax.swing.GroupLayout jPanel5Layout = new javax.swing.GroupLayout(jPanel5);
        jPanel5.setLayout(jPanel5Layout);
        jPanel5Layout.setHorizontalGroup(
            jPanel5Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(jPanel5Layout.createSequentialGroup()
                .addGap(14, 14, 14)
                .addComponent(jPanel6, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                .addComponent(jPanel4, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                .addGap(18, 18, 18)
                .addGroup(jPanel5Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addComponent(jLabel6)
                    .addComponent(jLabel9)
                    .addGroup(jPanel5Layout.createSequentialGroup()
                        .addGap(87, 87, 87)
                        .addComponent(jLabel2))
                    .addComponent(jLabel7)
                    .addComponent(jLabel5)
                    .addComponent(jLabel17))
                .addGap(24, 24, 24)
                .addGroup(jPanel5Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addComponent(MA, javax.swing.GroupLayout.DEFAULT_SIZE, 91, Short.MAX_VALUE)
                    .addComponent(CA)
                    .addComponent(HRA)
                    .addComponent(BS)
                    .addComponent(GS))
                .addContainerGap())
        );
        jPanel5Layout.setVerticalGroup(
            jPanel5Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(jPanel5Layout.createSequentialGroup()
                .addContainerGap()
                .addGroup(jPanel5Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, jPanel5Layout.createSequentialGroup()
                        .addGroup(jPanel5Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addComponent(jLabel17)
                            .addComponent(GS, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                        .addGap(15, 15, 15)
                        .addGroup(jPanel5Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                            .addComponent(BS, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                            .addComponent(jLabel5)))
                    .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, jPanel5Layout.createSequentialGroup()
                        .addComponent(jLabel2)
                        .addGap(120, 120, 120)))
                .addGap(20, 20, 20)
                .addGroup(jPanel5Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addComponent(HRA, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(jLabel6))
                .addGap(13, 13, 13)
                .addGroup(jPanel5Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(jLabel7)
                    .addComponent(CA, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(18, 18, 18)
                .addGroup(jPanel5Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(jLabel9)
                    .addComponent(MA, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addContainerGap(javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
            .addGroup(jPanel5Layout.createSequentialGroup()
                .addGroup(jPanel5Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addComponent(jPanel4, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(jPanel6, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(0, 22, Short.MAX_VALUE))
        );

        jPanel1.setBackground(new java.awt.Color(0, 153, 255));
        jPanel1.setBorder(javax.swing.BorderFactory.createLineBorder(new java.awt.Color(0, 0, 0), 5));

        jLabel18.setFont(new java.awt.Font("Tahoma", 3, 24)); // NOI18N
        jLabel18.setText("Income Tax and Car Tax");

        javax.swing.GroupLayout jPanel1Layout = new javax.swing.GroupLayout(jPanel1);
        jPanel1.setLayout(jPanel1Layout);
        jPanel1Layout.setHorizontalGroup(
            jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, jPanel1Layout.createSequentialGroup()
                .addContainerGap(175, Short.MAX_VALUE)
                .addComponent(jLabel18, javax.swing.GroupLayout.PREFERRED_SIZE, 337, javax.swing.GroupLayout.PREFERRED_SIZE)
                .addGap(144, 144, 144))
        );
        jPanel1Layout.setVerticalGroup(
            jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(jPanel1Layout.createSequentialGroup()
                .addContainerGap()
                .addComponent(jLabel18)
                .addContainerGap(javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
        );

        exit.setFont(new java.awt.Font("Tahoma", 1, 11)); // NOI18N
        exit.setText("Exit");
        exit.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                exitActionPerformed(evt);
            }
        });

        reset.setFont(new java.awt.Font("Tahoma", 1, 11)); // NOI18N
        reset.setText("Reset");
        reset.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                resetActionPerformed(evt);
            }
        });

        jLabel19.setFont(new java.awt.Font("Tahoma", 1, 14)); // NOI18N
        jLabel19.setText("TAXABLE INCOME");

        taxcredit.setFont(new java.awt.Font("Tahoma", 1, 14)); // NOI18N
        taxcredit.setText("TAX CREDIT");

        jButton2.setFont(new java.awt.Font("Tahoma", 1, 11)); // NOI18N
        jButton2.setForeground(new java.awt.Color(51, 0, 0));
        jButton2.setText("Calculate");
        jButton2.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton2ActionPerformed(evt);
            }
        });

        CALCULATE.setFont(new java.awt.Font("Tahoma", 1, 14)); // NOI18N
        CALCULATE.setForeground(new java.awt.Color(153, 0, 0));
        CALCULATE.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                CALCULATEActionPerformed(evt);
            }
        });

        test.setFont(new java.awt.Font("Tahoma", 0, 12)); // NOI18N
        test.setForeground(new java.awt.Color(102, 0, 0));

        TAXABLEINCOME.setFont(new java.awt.Font("Tahoma", 0, 12)); // NOI18N
        TAXABLEINCOME.setForeground(new java.awt.Color(102, 0, 0));

        jButton3.setFont(new java.awt.Font("Tahoma", 1, 11)); // NOI18N
        jButton3.setForeground(new java.awt.Color(51, 0, 0));
        jButton3.setText("Car tax");
        jButton3.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton3ActionPerformed(evt);
            }
        });

        CALCULATE1.setFont(new java.awt.Font("Tahoma", 1, 14)); // NOI18N
        CALCULATE1.setForeground(new java.awt.Color(153, 0, 0));
        CALCULATE1.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                CALCULATE1ActionPerformed(evt);
            }
        });

        javax.swing.GroupLayout layout = new javax.swing.GroupLayout(getContentPane());
        getContentPane().setLayout(layout);
        layout.setHorizontalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(layout.createSequentialGroup()
                        .addGap(0, 0, Short.MAX_VALUE)
                        .addComponent(taxcredit, javax.swing.GroupLayout.PREFERRED_SIZE, 91, javax.swing.GroupLayout.PREFERRED_SIZE)
                        .addGap(53, 53, 53))
                    .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, layout.createSequentialGroup()
                        .addContainerGap(javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, layout.createSequentialGroup()
                                .addComponent(jLabel19)
                                .addGap(44, 44, 44))
                            .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, layout.createSequentialGroup()
                                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING)
                                    .addComponent(reset)
                                    .addComponent(exit))
                                .addGap(59, 59, 59))))
                    .addGroup(layout.createSequentialGroup()
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addGroup(layout.createSequentialGroup()
                                .addGap(61, 61, 61)
                                .addComponent(jButton2)
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)
                                .addComponent(CALCULATE, javax.swing.GroupLayout.PREFERRED_SIZE, 90, javax.swing.GroupLayout.PREFERRED_SIZE))
                            .addGroup(layout.createSequentialGroup()
                                .addContainerGap()
                                .addComponent(TAXABLEINCOME, javax.swing.GroupLayout.PREFERRED_SIZE, 140, javax.swing.GroupLayout.PREFERRED_SIZE))
                            .addGroup(layout.createSequentialGroup()
                                .addGap(27, 27, 27)
                                .addComponent(test, javax.swing.GroupLayout.PREFERRED_SIZE, 102, javax.swing.GroupLayout.PREFERRED_SIZE)))
                        .addGap(0, 0, Short.MAX_VALUE))
                    .addGroup(layout.createSequentialGroup()
                        .addGap(52, 52, 52)
                        .addComponent(jButton3)
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                        .addComponent(CALCULATE1, javax.swing.GroupLayout.PREFERRED_SIZE, 90, javax.swing.GroupLayout.PREFERRED_SIZE)
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)))
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addComponent(jPanel5, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addGroup(layout.createSequentialGroup()
                        .addGap(36, 36, 36)
                        .addComponent(jPanel1, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)))
                .addContainerGap())
        );
        layout.setVerticalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(layout.createSequentialGroup()
                        .addGap(56, 56, 56)
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                            .addComponent(CALCULATE, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                            .addComponent(jButton2)))
                    .addComponent(jPanel1, javax.swing.GroupLayout.PREFERRED_SIZE, 60, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(18, 18, 18)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(layout.createSequentialGroup()
                        .addComponent(jPanel5, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                        .addGap(0, 0, Short.MAX_VALUE))
                    .addGroup(layout.createSequentialGroup()
                        .addComponent(reset)
                        .addGap(18, 18, 18)
                        .addComponent(exit)
                        .addGap(43, 43, 43)
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                            .addComponent(jButton3)
                            .addComponent(CALCULATE1, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                        .addComponent(taxcredit)
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                        .addComponent(test, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                        .addGap(18, 18, 18)
                        .addComponent(jLabel19)
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)
                        .addComponent(TAXABLEINCOME, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                        .addGap(52, 52, 52))))
        );

        pack();
    }// </editor-fold>                        

    private void BSActionPerformed(java.awt.event.ActionEvent evt) {                                   
BS.setText("");
    }                                  

    private void GSActionPerformed(java.awt.event.ActionEvent evt) {                                   
        GS.setText("");
    }                                  

    private void FBActionPerformed(java.awt.event.ActionEvent evt) {                                   
       FB.setText("");

    }                                  

    private void jButton2ActionPerformed(java.awt.event.ActionEvent evt) {                                         

        double ob1=Integer.parseInt(OB1.getText());
        double fb=Integer.parseInt(FB.getText());
        double  pf=Integer.parseInt(PF.getText());
        double  pfb=Integer.parseInt(PFB.getText());
        double  lf=Integer.parseInt(LF.getText());
       double ob=Integer.parseInt(OB.getText());
        double  gs=Integer.parseInt(GS.getText());
        double  li=Integer.parseInt(LI.getText());
        double sp=Integer.parseInt(SP.getText());
       double  sm=Integer.parseInt(SM.getText());
       double oi=Integer.parseInt(OI.getText());
      if(ob1==1500)
       {car=(car+25000);
        CALCULATE1.setText((car)+" ");
       car=0;}
       
       else if(ob1>=1500 && ob1<=2000)
       {car=(car+50000);
       CALCULATE1.setText((car)+" ");
       ob1=0;}
       else if(ob1>=2000 && ob1<=2500)
       {car=(car+75000);
      CALCULATE1.setText((car)+" ");
        car=0;
       }
       
       else if(ob1>=2500 && ob1<=3000)
       { car=(car+125000);
         CALCULATE1.setText((car)+" ");
        car=0;
       }
       
       else if(ob1>=3000 && ob1<=3500)
       {car=(car+150000);
      CALCULATE1.setText((car)+" ");
        car=0;
       }
       
       else if(ob1>=3500)
       { car=(car+200000);
     CALCULATE1.setText((car)+" ");
        car=0;
       }
     
        if(gs<250000){
            TAX=0;
            TC=0;
            tai=0;
        }
       
        else{
        double  bs=((gs*60)/100);
  double  hra=((gs*30)/100);
      double  ca=((gs*4)/100);
      double  ma=((gs*6)/100);
        BS.setText(bs+" ");
        HRA.setText(hra+" ");
        CA.setText(ca+" ");
        MA.setText(ma+" ");
        
      double  allow_investment=(li+sp+sm+oi);
     double  hrt=((bs*50)/100);// 50% of basic salary
       
      if(hra<hrt){
         tai=(fb+pf+pfb+lf+ob+bs+hrt);
       
      }
      else{
          hrt=0;
            tai=(fb+pf+pfb+lf+ob+bs+hrt);
          
      }
      if((ca/12)>2500)//if conveyance greater than 2500 per month then add to taxable income
      {
           tai=(fb+pf+pfb+lf+ob+bs+hrt+ca);
         
      }
      else{
         ca=0;
            tai=(fb+pf+pfb+lf+ob+bs+hrt+ca); 
      
      }
     double  mat=((bs*10)/100);//10% of basic salary 
         if(ma<mat){
              tai=(fb+pf+pfb+lf+ob+bs+hrt+ca+mat);
              
         } 
         else{
             mat=0;
              tai=(fb+pf+pfb+lf+ob+bs+hrt+ca+mat);
              
         }
         TAXABLEINCOME.setText(tai+" ");
          ttai1=(tai-250000);//on 1st 250000 0% tax
        if(0<ttai1 && ttai1<=400000 || ttai1>400000)
        {
             a=(ttai1*10)/100;//on next 400000 10% tax
               ttax=(a+b+c+d);
                 
         }
         else
         {
             a=0;
         }
         ttai2=(ttai1-400000);
       if(ttai2==500000 || ttai2>500000){
             b=(ttai2*15)/100;//on next 500000 15% tax
              ttax=(a+b+c+d);
               
         }
         else{
             b=0;
       }
         ttai3=(ttai2-500000);
      
        if(ttai3==600000 || ttai3>600000){
             c=(ttai3*20)/100;//on next 600000 20% tax
               ttax=(a+b+c+d);
            
         }
         else{
             c=0;
         }
       
        if(allow_investment>=1){//have allowable investment then 25% of taxt able income
            ali=((25*tai)/100);
              TC=((15*ali)/100);
             TAX =((ttax-TC));
        }
        else{ 
            TC=0;
            double  TAX =((ttax-TC));
        }
        
  
       // if (ob1==0)
        //{ car=0;
         //OB1.setText(car+" ");}
      
        
          test.setText(TC+" ");}
         CALCULATE.setText((TAX)+" ");
    }                                        

    private void CALCULATEActionPerformed(java.awt.event.ActionEvent evt) {                                          
       // CALCULATE.setText(jButton2+"");
    }                                         

    private void PFActionPerformed(java.awt.event.ActionEvent evt) {                                   
    PF.setText("");
    }                                  

    private void PFBActionPerformed(java.awt.event.ActionEvent evt) {                                    
PFB.setText("");
    }                                   

    private void LFActionPerformed(java.awt.event.ActionEvent evt) {                                   
       LF.setText("");
    }                                  

    private void OBActionPerformed(java.awt.event.ActionEvent evt) {                                   
       OB.setText("");
    }                                  

    private void HRAActionPerformed(java.awt.event.ActionEvent evt) {                                    
 
    }                                   

    private void CAActionPerformed(java.awt.event.ActionEvent evt) {                                   
        
    }                                  

    private void MAActionPerformed(java.awt.event.ActionEvent evt) {                                   
     
    }                                  

    private void LIActionPerformed(java.awt.event.ActionEvent evt) {                                   
     LI.setText("");
    }                                  

    private void SPActionPerformed(java.awt.event.ActionEvent evt) {                                   
    SP.setText("");
    }                                  

    private void SMActionPerformed(java.awt.event.ActionEvent evt) {                                   
     SM.setText("");
    }                                  

    private void OIActionPerformed(java.awt.event.ActionEvent evt) {                                   
   OI.setText("");
    }                                  

    private void exitActionPerformed(java.awt.event.ActionEvent evt) {                                     
 System.exit(0);    
    }                                    

    private void resetActionPerformed(java.awt.event.ActionEvent evt) {                                      
      BS.setText(0+"");
     HRA.setText(0+"");
  MA.setText(0+"");
    CA.setText(0+"");
 LI.setText(0+"");
    PF.setText(0+"");
  PFB.setText(0+"");
   LF.setText(0+"");
  OB.setText(0+"");
    SP.setText(0+"");
    FB.setText(0+"");
    SM.setText(0+"");
   OI.setText(0+"");
   OB1.setText(0+"");
    LI.setText(0+"");
    GS.setText(0+"");
    CALCULATE.setText(0+"");
    CALCULATE1.setText(0+"");
     TAXABLEINCOME.setText(0+"");
      test.setText(0+" ");
    }                                     

    private void FBFocusGained(java.awt.event.FocusEvent evt) {                               
        // TODO add your handling code here:
         if( FB.getText().toString().equals("0")){
             FB.setText("");}
    }                              

    private void FBFocusLost(java.awt.event.FocusEvent evt) {                             
        // TODO add your handling code here:
          if(FB.getText().toString().equals("")){
            FB.setText("0");}
    }                            

    private void PFFocusGained(java.awt.event.FocusEvent evt) {                               
        // TODO add your handling code here:
        if(PF.getText().toString().equals("0")){
             PF.setText("");}
    }                              

    private void PFFocusLost(java.awt.event.FocusEvent evt) {                             
        // TODO add your handling code here:
          if(PF.getText().toString().equals("")){
            PF.setText("0");}
    }                            

    private void PFBFocusLost(java.awt.event.FocusEvent evt) {                              
        // TODO add your handling code here:
          if(PFB.getText().toString().equals("")){
            PFB.setText("0");}
    }                             

    private void LFFocusLost(java.awt.event.FocusEvent evt) {                             
        // TODO add your handling code here:
          if(LF.getText().toString().equals("")){
            LF.setText("0");}
    }                            

    private void OBFocusLost(java.awt.event.FocusEvent evt) {                             
        // TODO add your handling code here:
          if(OB.getText().toString().equals("")){
            OB.setText("0");}
    }                            

    private void LIFocusLost(java.awt.event.FocusEvent evt) {                             
        // TODO add your handling code here:
          if(LI.getText().toString().equals("")){
            LI.setText("0");}
    }                            

    private void SPFocusLost(java.awt.event.FocusEvent evt) {                             
        // TODO add your handling code here:
         if(SP.getText().toString().equals("")){
            SP.setText("0");}
    }                            

    private void SMFocusLost(java.awt.event.FocusEvent evt) {                             
        // TODO add your handling code here:
         if(SM.getText().toString().equals("")){
            SM.setText("0");}
    }                            

    private void OIFocusLost(java.awt.event.FocusEvent evt) {                             
        // TODO add your handling code here:
         if(OI.getText().toString().equals("")){
            OI.setText("0");}
    }                            

    private void GSFocusLost(java.awt.event.FocusEvent evt) {                             
        // TODO add your handling code here:
         if(GS.getText().toString().equals("")){
            GS.setText("0");}
    }                            

    private void BSFocusLost(java.awt.event.FocusEvent evt) {                             
        // TODO add your handling code here:
         if(BS.getText().toString().equals("")){
            BS.setText("0");}
    }                            

    private void HRAFocusLost(java.awt.event.FocusEvent evt) {                              
        // TODO add your handling code here:
         if(HRA.getText().toString().equals("")){
            HRA.setText("0");}
    }                             

    private void CAFocusLost(java.awt.event.FocusEvent evt) {                             
        // TODO add your handling code here:
         if(CA.getText().toString().equals("")){
            CA.setText("0");}
    }                            

    private void MAFocusLost(java.awt.event.FocusEvent evt) {                             
        // TODO add your handling code here:
         if(MA.getText().toString().equals("")){
            MA.setText("0");}
    }                            

    private void PFBFocusGained(java.awt.event.FocusEvent evt) {                                
        // TODO add your handling code here:
        if( PFB.getText().toString().equals("0")){
             PFB.setText("");}
    }                               

    private void LFFocusGained(java.awt.event.FocusEvent evt) {                               
        // TODO add your handling code here:
        if( LF.getText().toString().equals("0")){
             LF.setText("");}
    }                              

    private void OBFocusGained(java.awt.event.FocusEvent evt) {                               
        // TODO add your handling code here:
        if( OB.getText().toString().equals("0")){
             OB.setText("");}
    }                              

    private void LIFocusGained(java.awt.event.FocusEvent evt) {                               
        // TODO add your handling code here:
        if( LI.getText().toString().equals("0")){
            LI.setText("");}
    }                              

    private void SPFocusGained(java.awt.event.FocusEvent evt) {                               
        // TODO add your handling code here:
        if( SP.getText().toString().equals("0")){
            SP.setText("");}
    }                              

    private void SMFocusGained(java.awt.event.FocusEvent evt) {                               
        // TODO add your handling code here:
        if( SM.getText().toString().equals("0")){
             SM.setText("");}
    }                              

    private void OIFocusGained(java.awt.event.FocusEvent evt) {                               
        // TODO add your handling code here:
          if( OI.getText().toString().equals("0")){
             OI.setText("");}
    }                              

    private void GSFocusGained(java.awt.event.FocusEvent evt) {                               
        // TODO add your handling code here:
        if( GS.getText().toString().equals("0")){
             GS.setText("");}
    }                              

    private void BSFocusGained(java.awt.event.FocusEvent evt) {                               
        // TODO add your handling code here:
        if( BS.getText().toString().equals("0")){
             BS.setText("");}
    }                              

    private void HRAFocusGained(java.awt.event.FocusEvent evt) {                                
        // TODO add your handling code here:
        if( HRA.getText().toString().equals("0")){
             HRA.setText("");}
    }                               

    private void CAFocusGained(java.awt.event.FocusEvent evt) {                               
        // TODO add your handling code here:
        if( CA.getText().toString().equals("0")){
             CA.setText("");}
    }                              

    private void MAFocusGained(java.awt.event.FocusEvent evt) {                               
        // TODO add your handling code here:
        if( MA.getText().toString().equals("0")){
             MA.setText("");}
    }                              

    private void OB1FocusGained(java.awt.event.FocusEvent evt) {                                
        // TODO add your handling code here:
        if( OB1.getText().toString().equals("0")){
             OB1.setText("");}
        
    }                               

    private void OB1FocusLost(java.awt.event.FocusEvent evt) {                              
        // TODO add your handling code here:
        if(OB1.getText().toString().equals("")){
            OB1.setText("0");}
    }                             

    private void OB1ActionPerformed(java.awt.event.ActionEvent evt) {                                    
        // TODO add your handling code here:
        OB1.setText("");
    }                                   

    private void jButton3ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        // TODO add your handling code here:
    }                                        

    private void CALCULATE1ActionPerformed(java.awt.event.ActionEvent evt) {                                           
        // TODO add your handling code here:
    }                                          

    public static void main(String args[]) {
        java.awt.EventQueue.invokeLater(new Runnable() {
            public void run() {
                new practice().setVisible(true);
            }
        });
    }

    // Variables declaration - do not modify                     
    private javax.swing.JTextField BS;
    private javax.swing.JTextField CA;
    private javax.swing.JTextField CALCULATE;
    private javax.swing.JTextField CALCULATE1;
    private javax.swing.JTextField FB;
    private javax.swing.JTextField GS;
    private javax.swing.JTextField HRA;
    private javax.swing.JTextField LF;
    private javax.swing.JTextField LI;
    private javax.swing.JTextField MA;
    private javax.swing.JTextField OB;
    private javax.swing.JTextField OB1;
    private javax.swing.JTextField OI;
    private javax.swing.JTextField PF;
    private javax.swing.JTextField PFB;
    private javax.swing.JTextField SM;
    private javax.swing.JTextField SP;
    private javax.swing.JTextField TAXABLEINCOME;
    private javax.swing.JButton exit;
    private javax.swing.JButton jButton2;
    private javax.swing.JButton jButton3;
    private javax.swing.JLabel jLabel1;
    private javax.swing.JLabel jLabel10;
    private javax.swing.JLabel jLabel11;
    private javax.swing.JLabel jLabel12;
    private javax.swing.JLabel jLabel13;
    private javax.swing.JLabel jLabel14;
    private javax.swing.JLabel jLabel15;
    private javax.swing.JLabel jLabel16;
    private javax.swing.JLabel jLabel17;
    private javax.swing.JLabel jLabel18;
    private javax.swing.JLabel jLabel19;
    private javax.swing.JLabel jLabel2;
    private javax.swing.JLabel jLabel20;
    private javax.swing.JLabel jLabel21;
    private javax.swing.JLabel jLabel3;
    private javax.swing.JLabel jLabel4;
    private javax.swing.JLabel jLabel5;
    private javax.swing.JLabel jLabel6;
    private javax.swing.JLabel jLabel7;
    private javax.swing.JLabel jLabel8;
    private javax.swing.JLabel jLabel9;
    private javax.swing.JPanel jPanel1;
    private javax.swing.JPanel jPanel4;
    private javax.swing.JPanel jPanel5;
    private javax.swing.JPanel jPanel6;
    private javax.swing.JButton reset;
    private javax.swing.JLabel taxcredit;
    private javax.swing.JTextField test;
    // End of variables declaration                   
}
