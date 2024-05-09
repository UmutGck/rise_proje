# rise_proje
//importlar

import Nat "mo:base/Nat";
import Nat64 "mo:base/Nat64";
import Cycles "mo:base/ExperimentalCycles";

//canister smart contact 
actor HelloCycles{
//değişkenler 
//let = immutable
//var = mutable

let limit = 10_000_000;

//fonk (query, update)

public func wallet_balance() : async Nat {

//return *** return .... ;
// return *** metin...
Cycles.balance()
//return Cycles.balance();
};

