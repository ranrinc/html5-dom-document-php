# IvoPetkov\HTML5DOMNodeList

Represents a list of DOM nodes.

```php
IvoPetkov\HTML5DOMNodeList extends ArrayObject implements Countable, Serializable, ArrayAccess, Traversable, IteratorAggregate {

	/* Constants */
	const int ARRAY_AS_PROPS
	const int STD_PROP_LIST

	/* Properties */
	public readonly int $length

	/* Methods */
	public IvoPetkov\HTML5DOMElement|null item ( int $index )

}
```

## Extends

##### [ArrayObject](http://php.net/manual/en/class.arrayobject.php)

## Implements

##### [Countable](http://php.net/manual/en/class.countable.php)

##### [Serializable](http://php.net/manual/en/class.serializable.php)

##### [ArrayAccess](http://php.net/manual/en/class.arrayaccess.php)

##### [Traversable](http://php.net/manual/en/class.traversable.php)

##### [IteratorAggregate](http://php.net/manual/en/class.iteratoraggregate.php)

## Constants

##### const int ARRAY_AS_PROPS

##### const int STD_PROP_LIST

## Properties

##### public readonly int $length

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The list items count

## Methods

##### public [IvoPetkov\HTML5DOMElement](ivopetkov.html5domelement.class.md)|null [item](ivopetkov.html5domnodelist.item.method.md) ( int $index )

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Returns the item at the specified index.

### Inherited from [ArrayObject](http://php.net/manual/en/class.arrayobject.php)

##### public [__construct](http://php.net/manual/en/arrayobject.construct.php) ( [  $array [,  $ar_flags [,  $iterator_class ]]] )

##### public void [append](http://php.net/manual/en/arrayobject.append.php) ( $value )

##### public void [asort](http://php.net/manual/en/arrayobject.asort.php) ( void )

##### public void [count](http://php.net/manual/en/arrayobject.count.php) ( void )

##### public void [exchangeArray](http://php.net/manual/en/arrayobject.exchangearray.php) ( $array )

##### public void [getArrayCopy](http://php.net/manual/en/arrayobject.getarraycopy.php) ( void )

##### public void [getFlags](http://php.net/manual/en/arrayobject.getflags.php) ( void )

##### public void [getIterator](http://php.net/manual/en/arrayobject.getiterator.php) ( void )

##### public void [getIteratorClass](http://php.net/manual/en/arrayobject.getiteratorclass.php) ( void )

##### public void [ksort](http://php.net/manual/en/arrayobject.ksort.php) ( void )

##### public void [natcasesort](http://php.net/manual/en/arrayobject.natcasesort.php) ( void )

##### public void [natsort](http://php.net/manual/en/arrayobject.natsort.php) ( void )

##### public void [serialize](http://php.net/manual/en/arrayobject.serialize.php) ( void )

##### public void [setFlags](http://php.net/manual/en/arrayobject.setflags.php) ( $flags )

##### public void [setIteratorClass](http://php.net/manual/en/arrayobject.setiteratorclass.php) ( $iteratorClass )

##### public void [uasort](http://php.net/manual/en/arrayobject.uasort.php) ( $cmp_function )

##### public void [uksort](http://php.net/manual/en/arrayobject.uksort.php) ( $cmp_function )

##### public void [unserialize](http://php.net/manual/en/arrayobject.unserialize.php) ( $serialized )

## Details

Location: ~/src/HTML5DOMNodeList.php

---

[back to index](index.md)

