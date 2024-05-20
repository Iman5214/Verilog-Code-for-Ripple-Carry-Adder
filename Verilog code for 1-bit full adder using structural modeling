// fpga4student.com: FPGA projects, Verilog projects, VHDL projects
// Verilog project: Verilog code for 4-bit ripple-carry adder
// Verilog code for 1-bit full adder
module fulladder(X, Y, Ci, S, Co);
  input X, Y, Ci;
  output S, Co;
  wire w1,w2,w3;
  //Structural code for one bit full adder
  xor G1(w1, X, Y);
  xor G2(S, w1, Ci);
  and G3(w2, w1, Ci);
  and G4(w3, X, Y);
  or G5(Co, w2, w3);
endmodule
