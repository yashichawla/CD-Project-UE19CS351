TO-DO

VarDef -> done, tested
AssignStmt -> done, not completely tested
IfStmt
WhileStmt
BinaryExpr
Identifier
IfExpr

LLVM IR
python main.py --mode llvm tests/llvm/var_decl.py

Execute LLVM IR 
python main.py --mode llvm tests/llvm/var_decl.py | lli