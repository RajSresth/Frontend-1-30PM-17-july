# Attributes of Ordered List:-
1. type: type attribute is used to specify which type of bullet you want to represent.

    type:_______      values:-(1,a,A,I,i)

2. start: start attribute specifies starting of the sequence and here start attribute only accepts the numbers.

    start="______"      values:- 1,2,3,....

3. reversed: reversed attribute is used to reverse the sequence of ordered list.


# Unordered List:- 
  It is group of related items represented in an unordered way i.e, bullets are not following any sequence.

  To create unordered list we use <ul></ul> tag. It is container tag.
with a description of each
  To create list item we use <li></li> tag.

# Attribute of Unordered List: 
1. Type: Type attribute is used to specify which type of bullet you want to represent.

    type="______"     (values:- disc, circle, square,none)



# Desciption List/ Dictionary List/ Definition List:-
1. Description list is a list of term  term.
2. To create description list we use <dl></dl> tag. It is container tag.
3. To create description term we use <dt></dt> tag. 
4. To create description definition we use <dd></dd> tag.
5. Description definition tag we have to write within description term tag.
6. Description term tag we have to write with in description list tag. 

    Syntax:- 
            <dl> Description List

                <dt> Description Term-1

                    <dd>Description Definition Tag</dd>
                </dt>

                <dt> Description Term-2
                
                    <dd>Description Definition Tag</dd>
                </dt>
            </dl>